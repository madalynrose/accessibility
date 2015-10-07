# accessibility
Easy-to-follow web accessibility process

## Content
* link
 * [ ] single <a> tag around all content linked to same href
 * [ ] alt-text
 * [ ] long-desc if necessary
 * [ ] recognizable as link
   * [ ] :focus state
    * [ ] styling
* image
 * [ ] alt-text
 * [ ] long-desc if necessary
* video
 * [ ]  link to text transcript
 * [ ] subtitles through <track> tag
* form
 * [ ] tab order follows a logical pattern
 * [ ] all form controls are labeled either by “aria-label”, <label> tag, or “for” attribute
 * [ ] “placeholder” attributes are not used in place of label
 * [ ] related form elements (e.g. radio buttons, check boxes) are grouped using <fieldset> and/or <legend> tags
* dynamic content
 * [ ] live region attributes are set
 * [ ] states & properties are set
 * [ ] functions triggered by mouse events also fire for :focus or similar keyboard events
* entire page 
 * [ ] page landmarks have appropriate roles
 * [ ] document outline made obvious through use of semantic markup and/or appropriate roles
 * [ ] colors have sufficient contrast ratio

## Testing
* [ ] [tenon.io](http://tenon.io)
 * [ ] paste in new html
 * [ ] no major issues are listed
* [ ]  page is navigable using only keyboard
 
 
