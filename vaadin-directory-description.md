[![Available in Vaadin_Directory](https://img.shields.io/vaadin-directory/v/vaadinincubator-breadcrumb.svg)](https://vaadin.com/directory/component/vaadinincubator-breadcrumb)
[![Stars in Vaadin_Directory](https://img.shields.io/vaadin-directory/stars/vaadinincubator-breadcrumb.svg)](https://vaadin.com/directory/component/vaadinincubator-breadcrumb)

# &lt;incubator-breadcrumb&gt;

[&lt;incubator-breadcrumb&gt;](https://vaadin.com/components/incubator-breadcrumb) is a Web Component providing an easy way to ask the user to confirm a choice, part of the [Vaadin components](https://vaadin.com/components).

[<img src="https://raw.githubusercontent.com/vaadin/incubator-breadcrumb/master/screenshot.png" width="200" alt="Screenshot of incubator-breadcrumb">](https://vaadin.com/components/incubator-breadcrumb)

## Example Usage

```html
  <incubator-breadcrumb header="Unsaved changes" confirm-text="Save" on-confirm="save"
    cancel on-cancel="cancel" reject reject-text="Discard" on-reject="discard">
    Do you want to save or discard your changes before navigating away?
  </incubator-breadcrumb>
```
