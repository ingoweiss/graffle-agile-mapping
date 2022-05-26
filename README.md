# Graffle Agile Mapping

A Graffle plugin for creating freeform maps of user stories the data elements of which can be kept in sync with an external data source

## Installation

1. Clone this repository to any location of your choosing
2. Open Graffle
3. Choose "Automation" > "Configure..." menu item to open the "Automation Configuration" dialog
4. Click "Add Linked Folder..." button
5. Choose this repository's folder
6. The "Sync Agile Map" action should now be available under the "Automation" menu

## Graffle Template

Use the "Template.graffle" file to build your maps. It has the following elements that are a prerequisite for the "Sync Agile Map" action to work:

1. A canvas called "Map"
2. A canvas called "Templates"
3. A story "card" template graphic (group) on the "Templates" canvas which has:
    1. The metadata "type" of "card"
    2. A text field with name "id_field"
    3. A text field with name "name_field"

As long as the story template has these characteristics, you can change it any way you want

## JSON Template

This plugin supports

