# Edit Fields

Each Workspace can have its own custom set of task fields. By default, the Tasks module comes with a set of built-in fields that are applicable to most projects. These include the following:

- Name: The task’s name. This is a required field.
- Status: The current completion status of the task. By default, new tasks are set to “open”. The status field has three built-in values (“open”, “in progress”, “closed”) but new values can be added. This is a required field.
- Assigned To: The user assigned to the task. When the task is created, this user will receive a notification that they have been assigned a new task. This is an optional field.
- Due Date: The date when the task is due. This is an optional field.
- Checklist: A simple checklist for breaking the task down into sub-tasks. This is an optional field.
- Description: A description of the task. The value in this field will be turned into a comment in the task’s comments feed when the task is created. This is an optional field.

From the Manage Task Fields pop-up, you can search for an existing field to modify, or click “New Field” to create a new field in this Workspace.

When creating a new field, you will be prompted to name the field. The field’s name must be unique in this Workspace. You will then be asked to select a field type. TIMU supports a variety of different field types:

- Boolean: A true of false value.
- Checklist: A simple list a checkable items.
- Date: Pick a date from a calendar.
- Dropdown: Pick from a single or multi-select list of values.
- Number: A numeric value.
- Text: A simple text field.

Once the field type is selected, you will need to define its parameters. All fields can be marked as required, which means that a task cannot be created unless a value is specified in that field. Dropdown fields need one or more values defined, and can be flagged as multi-select. Optionally, dropdown values can be color-coded. When you have finished defining the field’s parameters, click “Next”.

You can then create or modify more fields, or click “Save” to save your changes and update the Tasks module.

Note that deleting an existing field will permanently erase existing data that may have been entered into that field in this Tasks module.
