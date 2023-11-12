# API Reference

A reference article is information-oriented.
It provides a structured description of a product:
its APIs, classes, functions, configuration options, actions, and so on.
Start with a summary of what this reference article is about, and what the items you are describing are used for.

## Command

<include from="lib.md" element-id="reuse"/>

Syntax:

```shell
cmd [OPTIONS]
```

This command has the following options:
-f or --force: This option is used to force the command to perform an action, even if there are warnings or potential conflicts. When you use this option, the command will proceed without asking for confirmation or checking for certain conditions, essentially overriding any cautionary checks.

-v or --version: This option is used to display the version information of the command or the software it is associated with. It's helpful for checking which version of the command or software you are using.

-c or --cluster: This option is typically used in the context of managing or interacting with clusters, which could be clusters of computers or other resources.

## API 

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

<api-endpoint openapi-path="./../../example.yaml" method="get" endpoint="/another_example">
<response type="100">
<sample>pipi</sample>
</response>
</api-endpoint>

<seealso>
    <!--Provide links to related how-to guides, overviews, and tutorials.-->
</seealso>

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.
    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.