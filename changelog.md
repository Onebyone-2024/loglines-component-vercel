## release-2025.11.06.16.08.26
- New Component - Input Number
- New Component - Form Input Numner
- Refactor Measurement Input 
    - remove `type` , `useDecimalFormat`
    - add `maxLength`
- Create story for Form Measurement Input
- refactor global service `numberWithCommas`
- refactor global service `formatDecimalNumber
- remove all indonesia language comment`

## release-2025.11.01.08.42.42
fix bugs - checkbox on table

## release-2025.10.31.13.10.59
Dropdown Async - Improvement: add onInputChange prop

## release-2025.10.30.16.22.22
improvement dropdown creatable for red border error

## release-2025.10.30.16.18.43
improvement dropdown creatable for red border error


## release-2025.10.28.12.01.24
- Table Component - add custom screen breakpoint for listView to be shown

## release-2025.10.23.16.09.17
- improve form input - add props.useIndonesianDecimalFormat

## release-2025.10.23.15.49.30
- improve form input - add props.useIndonesianDecimalFormat


## release-2025.10.23.11.27.29
small update

## release-2025.10.17.09.20.25
- fix bugs - border color issue on date picker input

## release-2025.10.15.16.57.31
- add input-group class that use flex-1 to take remaining space

## release-2025.10.15.12.41.59
- Styling fixes for Measurement Input component
- Fix hover color not working
- Add styling for Formik error state
- Make component responsive when the height is adjusted
- Fix double border issue on focus
- Match styling with Dropdown component

## release-2025.10.15.12.40.58
- Styling fixes for Measurement Input component
- Fix hover color not working
- Add styling for Formik error state
- Make component responsive when the height is adjusted
- Fix double border issue on focus
- Match styling with Dropdown component

## release-2025.10.13.12.30.33
- improvement: Add additional prop selectedLabel for change label multiple data selections in the dropdown component
- improvement: date picker input add properties for custom format date 

## release-2025.10.09.17.38.15
- LabelData component - add additional props in component label data (icon classname, icon click, and subdata classname)


## release-2025.10.03.11.26.59
- Improvement on Toggle component - Add Props for functionality and more custom styles

## release-2025.10.01.16.48.52
- Formik error: all components now use the same error styling, with red-v3 applied to both the border and label.
- On focus: all components have consistent styling when focused, with the border and label highlighted.
- add stories for component

## release-2025.09.29.17.11.57
- implement auto build storybook and push to vercel repositories

## release-2025.09.29.17.02.15
- Improve monthYearPicker component - add minYear & maxYear

## release-2025.09.18.17.22.58
- on formatDecimalNumber-  Add≈ `toFixed` prop to number formatting

## release-2025.09.15.16.26.08
update dropdown asyn


## release-2025.09.01.13.21.23
- update dropdown-async - additional logic on multivalue 

## release-2025.08.28.15.11.45
- Enable Pre-checked value for table
- Utilize the resetCheckedInitialValue prop

## release-2025.08.28.14.30.44
- Re release -> release-2025.08.18.17.42.4
- bugfix - inconsistent font size caused by hardcoded value

## release-2025.08.28.12.35.10

-   add new props on table component: option overlay component position on prefix
-   inject css for prefix overlay component

## release-2025.08.19.12.28.28

bugfix - update funciont format decimal for useDecimal in from input

## release-2025.08.19.12.23.38

improvement - update funciont formatDecimal

## release-2025.08.19.12.06.43

realase

## release-2025.08.07.21.31.36

-   improvement - add loading indicator and empty image icon inside table
-   improvement - add loading indicator and empty image icon inside table-tree
-   improvement - add loading indicator and empty image icon inside table-list-view

## release-2025.08.07.13.33.03

-   improvement - add custom build on table tree
-   bugfix - dropdown multiselect get bolder when choosing many items
-   bugfix - inconsistent padding when height more than default (36px)

## release-2025.07.30.17.21.59

-   improvement - dropdown multi select, use chip to show selected information
-   improvement - create story for dropdown multi select when `isChip: true`
-   improvement - create story for dropdown creatable

## release-2025.07.29.18.32.08

-   improvement - change placeholder color on Input component
-   improvement - change placeholder font size 12
-   add variant image (orange)
-   fix bugs - option menu is hidden on table row

```
# add this on form dropdown
 menuPortalTarget={document.body}
```

-   improvement - fix date picker placeholder color
-   fix bugs - dropdown component selected not vertically center
-   add additional button on dropdown

## release-2025.07.24.16.13.27

-   fix bugs styling on table-tree

## release-2025.07.24.15.58.54

-   fix bugs - add missing export

## release-2025.07.24.15.52.59

-   add table-tree component

## release-2025.07.23.16.56.43

-   add dropdown creatable component
-   add dropdown form creatable component

## release-2025.07.23.13.40.43

update dropdown

## release-2025.07.23.13.40.08

update dropdown

## release-2025.07.23.11.37.06

testuing

## release-2025.07.21.12.54.03

-   change label focus color same as default

## release-2025.07.18.12.01.11

-   improvement - disable auto close on dropdown multiselect
-   fix bugs - eslint issue

## release-2025.07.17.13.40.37

-   add loadash/debounce on dropdown component
-   NOTE: Please install lodash & lodash.debounce , on project folder

```

"lodash": "^4.17.21",
"lodash.debounce": "^4.0.8"

```

## release-2025.07.16.15.28.08

-   fixbugs - dropdown async, implementing loadOptions & initial options

## release-2025.07.15.12.29.20

-   fix dropdown issue
-   add form dropdown async

## release-2025.07.14.00.31.08

-   refactor dropdown component in dropdown-2.component
-   add dropdown-async component

## release-2025.07.10.11.13.21

-   Improvement - Add Multi Select Checkbox for Async Select Dropdown Component

## release-2025.07.09.15.17.13

-   New Component: preview document
-   Fix bugs: modal animation impact on dropdown service

## release-2025.07.08.17.40.05

-   improve modal close on outside click
-   add animation horizontal / vertical , default vertical

```bash
example:
<Modal
   ...
   animation= {'vertical' | 'horizontal'>
>
{children}
</Modal>
```

## release-2025.07.04.01.59.11

-   add clear function on date picker component

## release-2025.07.01.16.58.40

-   dropdown - fix border color on focus
-   input - fix placeholder color
-   add tippy/@react

## release-2025.06.30.07.09.31

-   fix style bug on toast component

## release-2025.06.29.22.03.12

-   fix issue on export `button-popup.interface`

## release-2025.06.28.19.28.58

fix export issue:

-   Info-card-group.interface
-   item-list-info.interface
-   item-list-info.interface
-   rechart-interface.ts
-   estimation-info.ts

## release-2025.06.28.17.26.38

-   add `required` on date-picker-input component

## release-2025.06.28.16.59.18

-   resolve issue loading gif on table component
-   resolve issue no data image on table component
-   make changes on deploy script

## release-2025.06.27.00.28.41

-   change deploy script:

```bash
1. copy all css into folder dist/styles
2. create import css file into dist/index.css
```

old way, it make double tailwind implementation (in project and in loglines-component)

```bash
1. build css using tailwind -i --minify
2. will build all style including tailwind styling
3. copy all build result into dist/index.css
```

## release-2025.06.25.17.43.04

-   update readme.md
-   remove console in dropdown component
-   create function to get tag
-   disable debugging i18n

## release-2025.06.24.11.35.53

-   Remove Bugs

## release-2025.06.21.20.42.38

-   adding new changes for button, split table, and dropdown
-   add berge styling
-   improve berge styling

## release-2025.06.21.20.40.47

-   finishing script
-   initial project
-   add shell script for deploying on local and github
