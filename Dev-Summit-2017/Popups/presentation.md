<!-- .slide: data-background="../reveal.js/img/title.png" -->
<!-- .slide: class="title" -->
# Making Popups
Kelly Hutchins and Heather Gonzago

---

<div style="text-align: left">

<h1>Popup Demo Theater</h1>
<p><a href="Demos/1-default_popup.html">Default View popup</a> : This sample shows working directly with a MapView's popup. When content is set directly on the Popup instance it is not tied to a specific feature or layer. In this example, it may not be the best choice since the content is very generic and is applied to all of the features within the layer.</p>

<p><a href="Demos/2-popupTemplate.html">PopupTemplate on feature layer</a> : This sample shows setting the popup template directly within a feature layer. This template is set up to display the title and a very generic field description for the template's content.</p>

---

<div style="text-align: left">

<h1>Popup Demo Theater</h1>
<p><a href="Demos/1-default_popup.html">Default View popup</a> : This sample shows working directly with a MapView's popup. When content is set directly on the Popup instance it is not tied to a specific feature or layer. In this example, it may not be the best choice since the content is very generic and is applied to all of the features within the layer.</p>

<p><a href="Demos/2-popupTemplate.html">PopupTemplate on feature layer</a> : This sample shows setting the popup template directly within a feature layer. This template is set up to display the title and a very generic field description for the template's content.</p>

---

<div style="text-align: left">

<h1>Popup Demo Theater</h1>

<p><a href="Demos/3-multipleElements.html">Template with multiple elements</a>: This sample adds a a feature layer similar to the previous sample. In this specific case, the popup's template is formatted to work with multiple types of elements instead of just text (content). We add the <code>mediaInfos</code> element to display an image of the monster. In addition, we also add additional field information using the <code>fieldInfos</code> element. The popup is also docked to the side of the view to make room for the multiple elements. A listing of all the types of elements can be found in the <a href="https://developers.arcgis.com/javascript/latest/api-reference/esri-PopupTemplate.html#content">PopupTemplate.content API reference.</a></p>

<p><a href="Demos/4-popupFunctionContent.html">Popup content using functions</a>: It is also possible to set content for a popup using a custom function. In this sample, a link is provided in the content which opens up a new browser window and performs a Google search on that monster name.</p>

---

<div style="text-align: left">

<h1>Popup Demo Theater</h1>

<p><a href="Demos/5-popupTheme.html">Various themes to style your popup</a>: The widget framework has multiple themes. These can be a nice alternative to the default popup look. For additional information on this, please see the <a href="https://developers.arcgis.com/javascript/latest/guide/styling/index.html">Styling topic</a>. </p>

<p><a href="Demos/6-popupAction.html">Popup Action</a> : The Popup widget may contain one or more actions, or buttons, that allow users to execute a function when clicked. The default popup on the view contains an "Zoom in" action that is symbolized by a magnifying glass icon zoom-action. This sample demonstrates how to add custom actions to a Popup and a PopupTemplate. </p>
 
---

# Please take our survey
1. Download the Esri Events app and go to DevSummit
2. Select the session you attended
3. Scroll down to the "Feedback" section
4. Complete Answers, add a Comment, and Select "Submit"

![Submit Feedback](Images/submit-feedback.png)


---

<!--.slide: data-background="../reveal.js/img/end.png" -->

---
