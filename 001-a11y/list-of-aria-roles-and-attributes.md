# List of ARIA-Roles

## 0. Abstract

Do NOT use this set of roles, use the concrete roles instead.

* [**command**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/command_role) - Abstract role for all other interactive widget which can be triggered, e.g. `button`, `link` or `menuitem`.
* [**composite**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/composite_role) - Abstract role for all interactive widgets which consist of multiple other elements, e.g. `grid`, `select`, `spinbutton` or `tablist`.
* [**input**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/input_role) - Abstract role for all the other input elements like `checkbox`, `radio`, `textbox` and so on.
* [**landmark**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/landmark_role) - Abstract role for all other landmark roles like `banner`, `main` or `contentinfo`.
* [**range**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/range_role) - Abstract role for all the roles which represents a range of values: `meter`, `progressbar` and `slider`.
* [**roletype**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/roletype_role) - Abstract role for all other roles.
* [**section**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/section_role) and [**sectionhead**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/sectionhead_role) - Abstract role of all renderable structural containment components. Some of the examples are: `alert`, `note`, `tooltip`, `code`, `figure` and `subscript`.
* [**select**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/select_role) - Abstract role for the inputs which require user to select something, e.g. `listbox`, `menu`, `radiogroup` or `tree`.
* [**structure**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/structure_role) - Abstract role for all document structural roles. Some of the examples are: `document`, `rowgroup` and `sectionhead`.
* [**widget**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/widget_role) - Abstract role of any other focusable roles.
* [**window**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/window_role) - Abstract role for content which are separated and standalone from the rest part of the content. It only contains `dialog` as its sub role.

## 1. Informative

* [**alertdialog**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/alertdialog_role) - This role is used for a modal alert dialog, usually this is for notifying users of urgent information that demands immediate attention. It can be applied to e.g. a modal error dialog, a modal dialog asking user if they are sure about deleting something and so on.
* [**article**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/article_role) - The content should be treat as an article. It has its own title, paragraphs and so on. It could be forum posts, comments, newspaper articles and so on.
* [**comment**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/comment_role) - It indicates a comment/reaction to some content on the page, or to a previous comment. E.g. in a text editor, someone could have marked a piece of text, and added his opinion to it.
* [**definition**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/definition_role) and [**term**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/term_role) - It's not that useful at least in my case, skipping it for now.
* [**dialog**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/dialog_role) - A dialog, could either be modal or not, it is used to notifying user about something, or ask user for some reaction. It could be a popup showing update is finished, data is loaded or something like that.
* [**directory**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/directory_role) - Deprecated. Simply don't use it.
* [**document-structural**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/structural_roles) - Simply don't use this role, use e.g. `dl`, `blockquote`, `caption`, `code`, `figure`, `figcation`, etc.
* [**figure**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/figure_role) - It's used for the content like images, code snippets, or any other content that presents information in a different way to a regular flow of text. This could be replaced by `<figure>` and `<figcaption>` elements in HTML.
* [**generic**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/generic_role) - Simply don't use this. It is equivalent to `<div>` or `<span>` HTML elements.
* [**group**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/group_role) - A logical group of elements on the page, which is not included in the page's summary or table of contents. E.g. a field set.
* [**heading**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/heading_role) - Simply don't use this, use `<h1>` to `<h6>` instead.
* [**img**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/img_role) - A graphical presentation of information. Such as an SVG or so. And actually it is very important to add `img` role to the SVG, so that the screen reader is treating the SVG as a whole.
* [**list**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/list_role) and [**listitem**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/listitem_role) - Simply don't use this, use `<ul>`, `<ol>` and `<li>` instead.
* [**mark**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/mark_role) - Something which is highlighted. Equivalent to the HTML `<mark>` element.
* [**math**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/math_role) - Indicating the content is a piece of mathmatical expression.
* [**meter**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/meter_role) - Simply don't use it, use `<meter>` HTML element instead.
* [**none**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/none_role) and [**presentation**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/presentation_role) - Remove the semantical meanings from the HTML tag.
* [**note**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/note_role) - The side content or additive content to the main content. Usually some kind of explanations and so on.
* [**separator**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/separator_role) - It is semantically equivalent to the `<hr>` element, but it could also be focusable, in this case, it provides more information than a simple `<hr>` element.
* [**table**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/table_role) - Simply a table. the difference between `table` and `grid` is that table is readonly, whilc grid is interactive.
  - [**rowgroup**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/rowgroup_role) - Literally a group of rows or row headers.
  - [**rowheader**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/rowheader_role) - The header of a horizontal row of cells, e.g. the week number in a calendar.
  - [**row**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/row_role) - A horizontal row of cells.
  - [**columnheader**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/columnheader_role) - The header of a vertical column of cells, e.g. the week day in a calendar.
  - [**cell**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/cell_role) - A cell in the table.
* [**tooltip**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/tooltip_role) - A tooltip for an interactive element. Note, here "interactive element" is very important.

## 2. Landmarks

* [**banner**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/banner_role) - The global site header. Actually it is equivalent to the top-level of `<header>` element in HTML. So it should be containing e.g. a logo, company name, search, global navi and/or slogan, etc.
* [**complementary**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/complementary_role) - A supporting section that relates to the main content. Actually it is equivalent to the `<aside>` element in HTML. So it should usually contain for example the author information, and other recommended readings, etc.
* [**contentinfo**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/contentinfo_role) - It is equivalent to the HTML `<footer>` element. So it should usually contain copyright, nagivation links, privacy statements and so on.
* [**form**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/form_role) - Simply don't use this, use `<form>` element instead. But don't forget to add `aria-label` to the `<form>` element.
* [**main**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/main_role) - The primary content of a document. It is equivalent to the HTML `<main>` element. Use the HTML element over this role.
* [**navigation**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/navigation_role) - A major groups of links used for navigating through the website. It is equivalent to the HTML `<nav>` element. Use the HTML element over this role.
* [**region**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/region_role) - A section of content, which cannot be described by other landmark roles. It is equivalent to the HTML `<section>` element, so use the HTML element over this role.
* [**search**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/search_role) - The search functionality of the website. This is equivalent to the `<search>` element in HTML. So use HTML element.
* [**suggestion**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/suggestion_role) - It is like the comments in the Word. It marks a part of text, and say if it should be inserted or deleted. Use `<ins>` and `<del>` HTML elements are a better choice.

## 3. Live Region

* [**alert**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/alert_role) - It creates a live reaion for communicating an important and usually time-sensitive message to the user. It can be applied to e.g. invalid value was entered into a form field, login is failing and so on.
* [**log**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/log_role) - It creates a live region for communicating a sequence of messages which comes in a certain order. For example, chat, error log, game log and so on.
* [**marquee**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/marquee_role) - It creates a live region for communicating a piece of content which changes constantly. Comparing to `log` role, the content of `marquee` doesn't necessarily has a logical order.
* [**progressbar**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/progressbar_role) - Just a progress bar. Use `<progress>` HTML element over this role.
* [**status**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/status_role) - Works like a status bar in the `explorer.exe`. Just some extra information which is not that important but still nice-to-know to the user.
* [**timer**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/timer_role) - Warn the user of a numerical counter which is changing according to the time.

## 4. Interactive

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
* [**document**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/document_role) - Something is focusable, but can only be read instead of interactived. Usually combined with `tabindex=0`.
* [**feed**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/feed_role) - A dynamic scrollable list of articles, where articles are added or removed dynamically while **scrolling**. It is enabling user to use the reading cursor to read and scroll through a stream of rich content.
  - Press `Page Down` or `Page Up` to navigate through articles (only recommended, not built-in in browser)
  - Press `Control` + `End` to jump to the first focusable element after the feed (only recommended, not built-in in browser)
  - Press `Control` + `Home` to jump to the first focusable element before the feed (only recommended, not built-in in browser)
* [**grid**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/grid_role) or [**treegrid**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/treegrid_role) - It should be some content with in a logical grid, usually interactive, the best example would be calendar. Comparing to `grid` role, `treegrid` is only hierachical.
  - [**rowgroup**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/rowgroup_role) - Literally a group of rows or row headers.
  - [**rowheader**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/rowheader_role) - The header of a horizontal row of cells, e.g. the week number in a calendar.
  - [**row**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/row_role) - A horizontal row of cells.
  - [**columnheader**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/columnheader_role) - The header of a vertical column of cells, e.g. the week day in a calendar.
  - [**gridcell**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/cell_role) - If a cell is in the grid, it should be using the `gridcell` role, while `cell` role is only used in `table` 
  - Pressing `Up Arrow`, `Down Arrow`, `Left Arrow`, `Right Arrow` to navigate in the grid (only recommended, not built-in in browser)
  - Pressing `Page Down` or `Page Up` to jump down or up for a certain numbers of rows (only recommended, not built-in in browser)
  - Pressing `Home` to focus on the first cell in a row (only recommended, not built-in in browser)
  - Pressing `End` to focus on the last cell in a row (only recommended, not built-in in browser)
  - Pressing `Control` + `Home` to focus on the very first cell in the grid (only recommended, not built-in in browser)
  - Pressing `Control` + `End` to focus on the very last cell in the grid (only recommended, not built-in in browser)
  - Pressing `Space` or `Enter` to interact with the current focused gridcell.
* [**link**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/link_role) - Simply don't use this, use `<a>` element in HTML instead.
  - Pressing `Enter` to interact with it
* [**listbox**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/listbox_role) and [**option**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/option_role) - A list of components which are static and can be interacted with. E.g. the items in the combobox, or in a dropdown menu.
  - Pressing `Up Arrow` or `Down Arrow` to nagivate through the content.
  - Pressing `Home` to focus to the first option.
  - Pressing `End` to focus to the last option.
* [**menu**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/menu_role) or [**menubar**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/menubar_role) - Provide a list of choices to the user. Menu can be hidden or displayed, while menubar is usually always displayed. Menu is usually vertical, while menubar is usually horizontal.
  - [**menuitem**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/menuitem_role) - an item in the menu which is interactable.
  - [**menuitemcheckbox**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/menuitemcheckbox_role) - similar to `menuitem`, but it also provides a state of wheather it is selected or not.
  - [**menuitemradio**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/menuitemradio_role) - similar to `menuitemcheckbox`, but only one of them in a group can be selected at a certain time point.
  - Pressing `Enter` opens the menu, pressing `Enter` again or `Escape` closes the menu
  - Pressing `Space` or `Enter` to interact with the element in the menu
  - Pressing `Up Arrow` or `Down Arrow` to navigate through different items
  - Pressing `Home` or `End` to move to the first or the last item in the menu
* [**radiogroup**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/radiogroup_role) and [**radio**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/radio_role) - If it is possible, we should always use `<input type="radio">` instead of these two roles.
  - Pressing `Space` to active with one of the radio items
  - Pressing `Up Arrow`, `Down Arrow`, `Left Arrow` or `Right Arrow` to nagivate through different radio choices
* [**scrollbar**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/scrollbar_role) - This is used for the customized scrollbar.
  - Pressing `Up Arrow` or `Down Arrow` to scroll a little bit
  - Pressing `Page Up` or `Page Down` to scroll a huge chunk
  - Pressing `Space` to scroll down for a huge chunk
  - Pressing `Shift` + `Space` to scroll up for a huge chunk
* [**searchbox**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/searchbox_role) - Equivalent to the html `<input type="search">`, so simply use HTML instead of this role.
* [**slider**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/slider_role) - A slider, similar to `<input type="range">`, so use HTML element instead.
  - Pressing `Up Arrow`, `Down Arrow`, `Left Arrow` or `Right Arrorw` to adjust the value of the slider
  - Pressing `Home` or `End` to adjust the value to minimum or maximum
* [**spinbutton**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/spinbutton_role) - Spinbutton is a widget which consists of an input field, and a up button and a down button to adjust the value in the input field. It is recommended to use `<input type="number">` HTML element over this role.
  - Pressing `Up Arrow`, `Down Arrow`, `Left Arrow` or `Right Arrorw` to adjust the value
  - Pressing `Home` or `End` to adjust the value to minimum or maximum
* [**switch**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/switch_role) - Just a checkbox, usually we should use `<input type="checkbox">` instead of this role.
  - Pressing `Space` to check or uncheck it.
* [**tablist**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/tablist_role), [**tab**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/tab_role) and [**tabpanel**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/tabpanel_role) - This is forming a traditional tab widget. Tablist is a collection of tabs, and tab is the tab itself, while tabpanel is the content of the tab.
  - Pressing `Left Arrow` and `Right Arrow` to go through the tabs
* [**textbox**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/textbox_role) - This is equivalent to the HTML element `<input type="text">`, so use HTML element instead.
* [**toolbar**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/toolbar_role) - This is usually a group of buttons which provides different actions.
  - Pressing `Left Arrow` or `Right Arrow` to navigate through different buttons.
  - Pressing `Home` or `End` to navigate to the first or the last button.
* [**tree**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/tree_role) and [**treeitem**](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/treeitem_role) - Simply a treeview, for the folder structures for example.
  - Pressing `Right Arrow` to open a collapsed node
  - Pressing `Left Arrow` to close an expanded node
  - Pressing `Up Arrow` and `Down Arrow` to navigate through nodes
  - Pressing `Home` to focus on the first node
  - Pressing `End` to focus on the last node
  - Pressing `Enter` to interact with the selected node
  - Pressing `Space` to select a node
  - Pressing `Shift` + `Up Arrow` or `Shift` + `Down Arrow` to select multiple nodes
