---
title: Forms
category: Base
---

## Example form

<form class="form" action="#">
  <label class="form-field">
    <span class="block-label">Input</span>
    <input class="block-input" type="text" placeholder="A placeholder" />
  </label>
  <label class="form-field">
    <span class="block-label">Input</span>
    <input class="block-input" type="text" placeholder="A placeholder" />
  </label>
  <label class="form-field">
    <span class="block-label">Input</span>
    <input class="block-input" type="text" placeholder="A placeholder" />
  </label>
  <button class="btn btn--primary">Save</button>
</form>

```html
<form class="form" action="#">
  <label class="form-field">
    <span class="block-label">Input</span>
    <input class="block-input" type="text" placeholder="A placeholder" />
  </label>
  <label class="form-field">
    <span class="block-label">Input</span>
    <input class="block-input" type="text" placeholder="A placeholder" />
  </label>
  <label class="form-field">
    <span class="block-label">Input</span>
    <input class="block-input" type="text" placeholder="A placeholder" />
  </label>
  <button class="btn btn--primary">Save</button>
</form>
```

## Text input

`.block-input` fields will fill the width of their container. Paired with our grid system, we can easily create full and half width input fields.

<div class="row">
  <div class="col-12">
    <label class="form-field">
      <span class="block-label">Full width input</span>
      <input class="block-input" type="text" />
    </label>
  </div>
</div>
<div class="row">
  <div class="col-6">
    <label class="form-field">
      <span class="block-label">First half</span>
      <input class="block-input" type="email" />
    </label>
  </div>
  <div class="col-6">
    <label class="form-field">
      <span class="block-label">Second half</span>
      <input class="block-input" type="password" />
    </label>
  </div>
</div>

```html
<div class="row">
  <div class="col-12">
    <label class="form-field">
      <span class="block-label">Full width input</span>
      <input class="block-input" type="text" />
    </label>
  </div>
</div>
<div class="row">
  <div class="col-6">
    <label class="form-field">
      <span class="block-label">First half</span>
      <input class="block-input" type="email" />
    </label>
  </div>
  <div class="col-6">
    <label class="form-field">
      <span class="block-label">Second half</span>
      <input class="block-input" type="password" />
    </label>
  </div>
</div>
```

## Disabled text input

To disabled a text input you can set the property `disabled="true"`.

<label class="form-field">
  <span class="block-label">Disabled</span>
  <input class="block-input block-input--disabled" type="text" disabled="true" />
</label>

```html
<label class="form-field">
  <span class="block-label">Disabled</span>
  <input class="block-input block-input--disabled" type="text" disabled="true" />
</label>
```

## Text input with error

<label class="form-field">
  <span class="block-label">First name</span>
  <input class="block-input block-input--error" type="text" />
  <span class="block-label block-label--error">You can't leave this empty.</span>
</label>

```html
<label class="form-field">
  <span class="block-label">First name</span>
  <input class="block-input block-input--error" type="text" />
  <span class="block-label block-label--error">You can't leave this empty.</span>
</label>
```

## Submit button

<button type="submit" class="btn btn--block btn--primary">
  Submit button
</button>

```html
<button type="submit" class="btn btn--block btn--primary">
  Submit button
</button>
```

## Checkbox

To use a normal checkbox use the class name of `.checkbox`.

<label class="checkbox">
  <input type="checkbox" />
  <div class="checkbox__input"></div>
  <span class="checkbox__label">A checkbox</span>
</label>

<label class="checkbox">
  <input type="checkbox" disabled />
  <div class="checkbox__input"></div>
  <span class="checkbox__label">A disabled checkbox</span>
</label>

<label class="checkbox">
  <input type="checkbox" />
  <div class="checkbox__input"></div>
  <span class="checkbox__label">
    Dolore adipisicing hic voluptas, sed! Porta? Consectetur quia, in euismod eleifend tellus, commodo laborum per! Suscipit ullamcorper animi quos ullamco quos! Possimus ut semper? Felis.
  </span>
</label>

```html
<label class="checkbox">
  <input type="checkbox" />
  <div class="checkbox__input"></div>
  <span class="checkbox__label">A checkbox</span>
</label>

<label class="checkbox">
  <input type="checkbox" disabled />
  <div class="checkbox__input"></div>
  <span class="checkbox__label">A disabled checkbox</span>
</label>

<label class="checkbox">
  <input type="checkbox" />
  <div class="checkbox__input"></div>
  <span class="checkbox__label">
    Dolore adipisicing hic voluptas, sed! Porta? Consectetur quia, in euismod eleifend tellus, commodo laborum per! Suscipit ullamcorper animi quos ullamco quos! Possimus ut semper? Felis.
  </span>
</label>
```

You can make checkboxes inline with `.checkbox--inline`.

<label class="checkbox checkbox--inline">
  <input type="checkbox" />
  <div class="checkbox__input"></div>
  <span class="checkbox__label">A checkbox</span>
</label>

<label class="checkbox checkbox--inline margin1--left">
  <input type="checkbox" />
  <div class="checkbox__input"></div>
  <span class="checkbox__label">A checkbox</span>
</label>

```html
<label class="checkbox checkbox--inline">
  <input type="checkbox" />
  <div class="checkbox__input"></div>
  <span class="checkbox__label">A checkbox</span>
</label>
```

## Nested checkbox

To add a checkbox nested under a parent input use the additional class name of `.checkbox--nested`.

<label class="form-field checkbox checkbox--nested">
  <input type="checkbox" />
  <div class="checkbox__input"></div>
  <span class="checkbox__label">A nested checkbox</span>
</label>

```html
<label class="form-field checkbox checkbox--nested">
  <input type="checkbox" />
  <div class="checkbox__input"></div>
  <span class="checkbox__label">A nested checkbox</span>
</label>
```

## Radio

To use a normal inline radio use the class name of `.radio`.

<label class="form-field radio radio--nested">
  <input class="radio__input" type="radio" />
  <span class="radio__label">A radio</span>
</label>

```html
<label class="form-field radio radio--nested">
  <input class="radio__input" type="radio" />
  <span class="radio__label">A radio</span>
</label>
```

## Select

Select dropdowns will take up the full width of their container.

<label class="form-field">
  <span class="block-label">Dropdown label</span>
  <select required>
    <option value="" hidden disabled selected>Select an option</option>
    <option value="1">Option 1</option>
    <option value="2">Option 2</option>
    <option value="3">Option 3</option>
  </select>
</label>

```html
<label class="form-field">
  <span class="block-label">Dropdown label</span>
  <select required>
    <option value="" hidden disabled selected>Select an option</option>
    <option value="1">Option 1</option>
    <option value="2">Option 2</option>
    <option value="3">Option 3</option>
  </select>
</label>
```

## Textarea

<textarea class="block-input"></textarea>

```html
<textarea class="block-input"></textarea>
```
