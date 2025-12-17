## release-2025.12.17.20.14.33
-   improvement - improve tab-master component responsive sizing:
    -   added xl breakpoint grid layout (xl:grid xl:grid-cols-5) for better desktop alignment
    -   title now spans full width on xl screens (xl:col-span-5)
    -   tabs section constrained to 3 columns on xl screens (xl:col-span-3)
    -   search and buttons section spans 2 columns on xl screens (xl:col-span-2)
    -   improved responsive behavior across all screen sizes

## release-2025.12.17.19.47.27
- refactor dropdown, dropdown-async, and dropdown-creatable components with
  custom clear and dropdown indicators for consistent icon styling
- enhance date-picker-input component with unified icon/clearable layout,
  improved disabled state, and fixed heights for icons and separator
- add focus state CSS classes to measurement-input for better visual feedback
- improve disabled state visual consistency across form components

## release-2025.12.17.20.07.55
-   improvement - improve tab-master component responsive sizing:
    -   added xl breakpoint grid layout (xl:grid xl:grid-cols-5) for better desktop alignment
    -   title now spans full width on xl screens (xl:col-span-5)
    -   tabs section constrained to 3 columns on xl screens (xl:col-span-3)
    -   search and buttons section spans 2 columns on xl screens (xl:col-span-2)
    -   improved responsive behavior across all screen sizes

## release-2025.12.17.16.30.00
-   improvement - refactor dropdown components (dropdown, dropdown-async, dropdown-creatable) with custom clear and dropdown indicators for consistent icon styling
-   improvement - enhance date-picker-input component:
    -   unified icon and clearable button layout using absolute positioning
    -   improved disabled state visual feedback
    -   fixed icon container and separator heights for better consistency
    -   added click prevention when disabled
-   improvement - enhance measurement-input component:
    -   added CSS classes for focused label and border states
    -   improved focus state visual consistency

## release-2025.12.17.15.02.06
improvment component pils and also add new variant color for brand-v3

## release-2025.12.16.19.18.49
-   improvement - add `asteriskPosition` prop support to:
    -   `dropdown-async` component: required asterisk can now be positioned before or after the label using `asteriskPosition` prop
    -   `dropdown-creatable` component: required asterisk can now be positioned before or after the label using `asteriskPosition` prop
    -   `form-dropdown-creatable` component: passes `asteriskPosition` prop to dropdown-creatable for consistent required asterisk placement

## release-2025.12.16.18.10.55

fix bugs - add `additional.css` for global css (exclude tailwind)

## release-2025.12.16.17.12.52

-   improvement - add `asteriskPosition` prop ('before' | 'after') to all form components for flexible required asterisk placement:
    -   `form-input`
    -   `form-date-picker`
    -   `form-dropdown`
    -   `form-input-file`
    -   `form-input-number`
    -   `form-measurement-input`
    -   `form-phone-input`
    -   `form-textarea`
    -   `form-checkbox`
    -   `form-radio`
    -   `form-toggle-switch`
    -   `form-month-year-picker`
-   improvement - add `asteriskPosition` prop to base components:
    -   `input`
    -   `input-number`
    -   `dropdown`
    -   `date-picker`
    -   `measurement-input`
    -   `text-area`
-   improvement - create comprehensive Storybook stories for `form-measurement-input` component with 15 examples showcasing all features

## release-2025.12.16

-   improvement - add `asteriskPosition` prop ('before' | 'after') to all form components for flexible required asterisk placement:
    -   `form-input`
    -   `form-date-picker`
    -   `form-dropdown`
    -   `form-input-file`
    -   `form-input-number`
    -   `form-measurement-input`
    -   `form-phone-input`
    -   `form-textarea`
    -   `form-checkbox`
    -   `form-radio`
    -   `form-toggle-switch`
    -   `form-month-year-picker`
-   improvement - add `asteriskPosition` prop to base components:
    -   `input`
    -   `input-number`
    -   `dropdown`
    -   `date-picker`
    -   `measurement-input`
    -   `text-area`
-   improvement - create comprehensive Storybook stories for `form-measurement-input` component with 15 examples showcasing all features

## release-2025.12.15.17.39.56

-   improvement - add new option `iconClassName` and `optionContainerClassname` on `IDropdownItem`

## release-2025.12.10.12.03.59

-   improvement - add `isClearable` props on date picker

## release-2025.12.09.12.49.32

-   improvement - add `string` type on tab classname

## release-2025.12.04.13.33.52

-   improvement - add purple color on itabitem interface

## release-2025.12.04.13.32.14

-   improvement - add purple color on itabitem interface

## release-2025.12.03.11.13.48

-   improvement - improve default options on dropdown async

## release-2025.12.03.11.10.30

-   improvement - improve `defaultOptions` on dropdown async

## release-2025.11.28.14.48.57

improvement all table for data null and undefined

## release-2025.11.28.14.18.31

improvement for data null or undifiend

## release-2025.11.28.02.26.41

-   Improvement - add props `closeModalOnOutsideClick` to handle outside click modal

## release-2025.11.28.00.47.57

-   improvement - add `additional on checked` on FormCheckbox

## release-2025.11.27.22.38.35

-   improvement - barcode scanner add props `facing mode` to decide front / back camera

## release-2025.11.07.11.15.15

-   improvement: add props disable on item button popup

## release-2025.11.06.16.19.24

-   New Component - Input Number
-   New Component - Form Input Numner
-   Refactor Measurement Input
    -   remove `type` , `useDecimalFormat`
    -   add `maxLength`
-   Create story for Form Measurement Input
-   refactor global service `numberWithCommas`
-   refactor global service `formatDecimalNumber
-   remove all indonesia language comment`

## release-2025.11.06.16.08.26

-   New Component - Input Number
-   New Component - Form Input Numner
-   Refactor Measurement Input
    -   remove `type` , `useDecimalFormat`
    -   add `maxLength`
-   Create story for Form Measurement Input
-   refactor global service `numberWithCommas`
-   refactor global service `formatDecimalNumber
-   remove all indonesia language comment`

## release-2025.11.01.08.42.42

fix bugs - checkbox on table

## release-2025.10.31.13.10.59

Dropdown Async - Improvement: add onInputChange prop

## release-2025.10.30.16.22.22

improvement dropdown creatable for red border error

## release-2025.10.30.16.18.43

improvement dropdown creatable for red border error

## release-2025.10.28.12.01.24

-   Table Component - add custom screen breakpoint for listView to be shown

## release-2025.10.23.16.09.17

-   improve form input - add props.useIndonesianDecimalFormat

## release-2025.10.23.15.49.30

-   improve form input - add props.useIndonesianDecimalFormat

## release-2025.10.23.11.27.29

small update

## release-2025.10.17.09.20.25

-   fix bugs - border color issue on date picker input

## release-2025.10.15.16.57.31

-   add input-group class that use flex-1 to take remaining space

## release-2025.10.15.12.41.59

-   Styling fixes for Measurement Input component
-   Fix hover color not working
-   Add styling for Formik error state
-   Make component responsive when the height is adjusted
-   Fix double border issue on focus
-   Match styling with Dropdown component

## release-2025.10.15.12.40.58

-   Styling fixes for Measurement Input component
-   Fix hover color not working
-   Add styling for Formik error state
-   Make component responsive when the height is adjusted
-   Fix double border issue on focus
-   Match styling with Dropdown component

## release-2025.10.13.12.30.33

-   improvement: Add additional prop selectedLabel for change label multiple data selections in the dropdown component
-   improvement: date picker input add properties for custom format date

## release-2025.10.09.17.38.15

-   LabelData component - add additional props in component label data (icon classname, icon click, and subdata classname)

## release-2025.10.03.11.26.59

-   Improvement on Toggle component - Add Props for functionality and more custom styles

## release-2025.10.01.16.48.52

-   Formik error: all components now use the same error styling, with red-v3 applied to both the border and label.
-   On focus: all components have consistent styling when focused, with the border and label highlighted.
-   add stories for component

## release-2025.09.29.17.11.57

-   implement auto build storybook and push to vercel repositories

## release-2025.09.29.17.02.15

-   Improve monthYearPicker component - add minYear & maxYear

## release-2025.09.18.17.22.58

-   on formatDecimalNumber- Add≈ `toFixed` prop to number formatting

## release-2025.09.15.16.26.08

update dropdown asyn

## release-2025.09.01.13.21.23

-   update dropdown-async - additional logic on multivalue

## release-2025.08.28.15.11.45

-   Enable Pre-checked value for table
-   Utilize the resetCheckedInitialValue prop

## release-2025.08.28.14.30.44

-   Re release -> release-2025.08.18.17.42.4
-   bugfix - inconsistent font size caused by hardcoded value

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
