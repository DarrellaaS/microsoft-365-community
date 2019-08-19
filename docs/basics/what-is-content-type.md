# What is a Content Type?

## Basic Idea

The easy answer here is a Content Type is a type of content, but that isn't very helpful. A Content Type is like a business object: something that you move around your desk or computer every day.

## Real World Example

You work with Content Types at home every day. You probably have grocery lists, bills, and maybe a mortgage around your house right now. Each of these objects are second nature to you; you don't think about what they are or what to call them.

For sake of discussion, lets say you do have a mortgage and you've put it into a mnailla folder in your drawer.

![Document in a manilla folder](../../images/what-is-content-type/folder.png)

Wouldn't it be useful if you wrote some things on the outside of the folder so you could identify what was inside more easily? Maynbbe you'd add the data the mortgage was signed, the mortgage company, their phone number, and how much the mortgage was for.

![Document in a manilla folder with metadata](../../images/what-is-content-type/folder-with-metadata.png)

Now, you may wonder why we're looking at a foolder at all. Folders are supposed to be bad! But the analogy holds up: the folder in like the skin of the document, and we've added metadata on the outside to help us make sense of it.

## Back to Work

Now imagine you work at a mortgage company. Instead of one (or maybe two) mortgages, you're responsible for thousands. The Conternt Type becomes even more important, and you may want some additional metadata, like maybe the mortgage originator, the servicing company, and the mortgage due date.

![Document in a manilla folder with metadata](../../images/what-is-content-type/folder-with-more-metadata.png)

We don't add these metadata columns just for fun. We decide to collect the metadata which will enable the use cases we want. For example, if we'd like to have a view which shows all the morgages whish are going to be due in the next month, we need the Content Type = Mortgage and the mortgage due date >= [Today] and mortgage due date <= [Today+30]. We can't satisfy that use case unless we've made the document a Mortagage and added the mortgage due date metadata column.