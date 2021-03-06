### Markdown
Markdown card is used to render [markdown](http://commonmark.org/help/)

![markdown](https://user-images.githubusercontent.com/7738048/41775900-7269b8c8-762e-11e8-90f9-5634783d283e.png)

**Options**

| Name | Type | Default | Description
| ---- | ---- | ------- | -----------
| type | string | **Required** | `markdown`
| content | string | **Required** | Content to render as [markdown](http://commonmark.org/help/).
| title | string | Optional | Card title

**Example**

```yaml
- type: markdown
  content: >
    ## Lovelace

    Starting with Home Assistant 0.72, we're experimenting with a new way of defining your interface. We're calling it the **Lovelace UI**.
```

### Feedback
- ~Support templating [#55](https://github.com/home-assistant/ui-schema/issues/55)~
