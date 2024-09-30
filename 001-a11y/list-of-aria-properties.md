# List of ARIA-Roles and ARIA-Attributes

## 1. Roles

### 1.1. Informative

* [**alert**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/alert_role) - This role is used for communicating an important and usually time-sensitive message to the user. It can be applied to e.g. invalid value was entered into a form field, login is failing and so on.
* [**alertdialog**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/alertdialog_role) - This role is used for a modal alert dialog, usually this is for notifying users of urgent information that demands immediate attention. It can be applied to e.g. a modal error dialog, a modal dialog asking user if they are sure about deleting something and so on.
* [**article**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/article_role) - The content should be treat as an article. It has its own title, paragraphs and so on. It could be forum posts, comments, newspaper articles and so on.
* [**comment**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/comment_role) - It indicates a comment/reaction to some content on the page, or to a previous comment. E.g. in a text editor, someone could have marked a piece of text, and added his opinion to it.
* [**definition**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/definition_role) - It's not that useful at least in my case, skipping it for now.
* [**dialog**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/dialog_role) - A dialog, could either be modal or not, it is used to notifying user about something, or ask user for some reaction. It could be a popup showing update is finished, data is loaded or something like that.
* [**directory**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/directory_role) - Simply don't use it.
* [**document-structural**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/structural_roles) - Simply don't use this role, use e.g. `dl`, `blockquote`, `caption`, `code`, `figure`, `figcation`, etc.
* [**table**]():
  - [**row**]() - 
  - [**columnheader**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/columnheader_role) - 
  - [**cell**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/cell_role) - 

### 1.2. Landmarks

* [**banner**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/banner_role) - The global site header. Actually it is equivalent to the top-level of `<header>` element in HTML. So it should be containing e.g. a logo, company name, search, global navi and/or slogan, etc.
* [**complementary**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/complementary_role) - A supporting section that relates to the main content. Actually it is equivalent to the `<aside>` element in HTML. So it should usually contain for example the author information, and other recommended readings, etc.
* [**contentinfo**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/contentinfo_role) - It is equivalent to the HTML `<footer>` element. So it should usually contain copyright, nagivation links, privacy statements and so on.

### 1.3. Interactive

* [**application**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/application_role) - Tell the assistive technologies not to treat the current element and also its child elements as HTML, but only as desktop application. In this case, most of the assistive technologies will be disabled.
  - We have to implement the interactions on our own.
* [**button**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/button_role) - Usually we should use `<button>` or `<input role="button">`. This is only tricking the screen reader to treat an element as a button.
  - Pressing `Enter` or `Space` will activate the button.
* [**checkbox**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/checkbox_role) - Usually should be replaced by `<input type="checkbox">` with an associated `<label>`. This is only tricking the screen reader to treat an element as a checkbox.
  - Pressing `Space` will activate the checkbox.
* [**combobox**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/combobox_role) - A combination of an input and a popup, where user can select something from it. It could be an `<input>` element with a `<datalist>` popping up, or anything else which can achieve this goal. See the MDN document for a proper HTML structure of a combobox implementation.
  - Pressing `Down Arrow` to move the focus to the first option, if the current focus is in the input.
  - Pressing `Up Arrow` or `Down Arrow` to navigate through different options in the popup list.
  - Pressing `Enter` will select the currently focused popup list item.
* [**command**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/command_role) - Simply don't use this role, use `button`, `link` or `menuitem` instead.
* [**composite**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/composite_role) - Simply don't use this role, use `grid`, `select`, `spinbutton` or `tablist`.
* [**document**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/document_role) - Something is focusable, but can only be read instead of interactived. Usually combined with `tabindex=0`.
* [**feed**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/feed_role) - 
