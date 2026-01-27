
# Example links

Mastery LS makes it easy to create links between topics and even other courses. To create a link you just use the Markdown links syntax to reference your target content. If the content is a instructional topic then the link will resolve as if the user had navigated to the topic. If the link references a file then they file will display.

## Content structure

```
├ readme.md - Home (330b3872-aab6-442f-ac17-c6730d7502ed)
├ Examples
│   └ Links (c84f4f2e-2ecd-414a-bcfb-65cf10516e77)
│        ├ links.md
│        └ Main.java
└ Assorted topics
    └ cheese-2 (140d86ce-9e9b-4ce5-9fd0-95bb959c9df4)
         └ cheese-2.md
```

## Absolute URL

Open in new tab.

- [https://byu.edu](https://byu.edu)


## Anchor Link

Scroll to the link target. Any heading can be used as the target.

- [#target](#target) - anchor in this topic


## Root-relative URL

Open to the course or topic.

- [Topic in this course](/course/51a72d23-50ab-4147-a1db-27a062aed771/topic/140d86ce-9e9b-4ce5-9fd0-95bb959c9df4)
- [Web programming course](course/1a8c01d0-5e9c-4a7c-8597-55bd5159967e/topic/6d489420-b320-4bc9-b43d-5c041a08b6bf)

## Relative URL

Open either a topic or a resource of a topic in the current course

- [Main.java](./Main.java) - resource in current topic
- [./Main.java](./Main.java) - resource in current topic
- [../cheese-2/cheese-2.md](../cheese-2/cheese-2.md) - same parent topic folder
- [../../README.md](../../README.md) - root folder

## Image Link

Render the link as an image.

![Topic Cover](https://raw.githubusercontent.com/csinstructiontemplate/emptycourse/refs/heads/main/cover.jpg)


## Target

This is an example target for an internal link.

- [Return](#anchor-link)
