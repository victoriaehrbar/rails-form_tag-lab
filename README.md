# Rails form_tag Lab

## Objectives

1. Build a functional Rails form using a `form_tag`
2. Pass a route helper as the argument to a `form_tag`
3. Pass an options hash with a method to a `form_tag`
4. Use a `text_field_tag` and other form controls to create inputs
5. Build a `new` action that renders a form that submits to the `create` action

## Instructions

The two specs for this lab that are currently failing are located within the
`form page` feature in `specs/features/student_spec.rb`.

For this lab, you need to build a form to create a new student, create a new
student using `params` in the `create` route, and redirect to the `index` route
to display all the students. Below are a few items to keep in mind:

- Draw a `new` and `create` route for the `students` resource
- Create a student using the data from the form via `params`. If you're not sure
  how the params are being sent from the form, use `byebug` in your route or
  `puts` to display the params in the terminal.
- Redirect to the `index` route where all students will be displayed

## Keys to remember

- Look at the tests to see which field values you should be using

- Make sure to use the `form_tag` helpers

## Resources

- [Reading](https://github.com/learn-co-curriculum/rails-form_tag-readme)
- [Form Helper Documentation](http://api.rubyonrails.org/classes/ActionView/Helpers/FormTagHelper.html)
