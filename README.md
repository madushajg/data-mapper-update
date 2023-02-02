# data-mapper-update
## What's New

### Language Related
1. Expand support for various types of inputs and outputs other than records (basic types, arrays and inline records)
   ![array-io](resources/array-io.gif)


2. Enable adding all the intermediate clauses within query expressions with improved UI
   ![array-io](resources/intermediate-clauses.gif)


3. Add new input node to denote mappings associated with module declarations
   ![array-io](resources/module-var.gif)


4. Add local variable declaration support at the function level
   ![array-io](resources/local-var.gif)


5. Enable selecting types from imported packages as inputs and output types
   ![array-io](resources/imports.gif)


6. Add support for union type outputs
   ![array-io](resources/union-output.gif)


7. Add support for optional input record fields
    ![array-io](resources/optional-fields.gif)


8. Enable mapping with query expressions for primitive type arrays
    ![array-io](resources/primitive-query.gif)


### Usability Improvements
1. Enable opening the Data Mapper through ‘Design’ code lens
   ![array-io](resources/design-code-lens.gif)


2. Add support to access query expressions defined within let expressions
   ![array-io](resources/let-expr-query.gif)


3. Function name validation with unique name suggestions
   ![array-io](resources/fn-name-validation.gif)


4. Improvements in ports and links selection (select, deselect, disable parent ports if children mapped, etc)
    ![array-io](resources/port-selection.gif)


5. UI/UX improvements in link creations and deletions with loaders
    ![array-io](resources/loaders.gif)


6. Delete support for custom values, arrays and array elements
    ![array-io](resources/delete.gif)


7. Improvements in fields (display required fields, disable fields when the port is disabled)
    ![array-io](resources/dissabled-fields.gif)


8. Add tooltip in link with code actions
    ![array-io](resources/tooltip.png)


9. Add diagnostics tooltip to the link label
    ![array-io](resources/diagnostics.png)


10. Gracefully handle the Data Mapper view when user makes incompatible changes using the code editor
    ![array-io](resources/selected-fn.gif)


11. Add reset and fit-to-screen options
    ![array-io](resources/reset-screen.gif)


## In progress:

1. Add support for mappings with indexed query expressions
2. Provide search capability for filtering input, output fields

## Feature Backlog:

1. Auto update the function signature to include error return when required
2. Provide in-place record editing capability
3. Add support for table types
4. Improve the overall UX to be consistent with project-architecture view and the graphql views
5. Add support for keyboard shortcuts
6. Provide support for changing the mapped attributes without deleting the links
7. Improve UX for handling open records or var typed let variables in Data Mapper
8. Add support to extract expressions to local variables
