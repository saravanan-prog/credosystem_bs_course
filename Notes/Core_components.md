## 🔘 1. Buttons

Used for actions like submit, cancel, click events.

#### Example:

```
    <button class="btn btn-primary">Primary</button>
    <button class="btn btn-success">Success</button>
    <button class="btn btn-danger">Delete</button>
```

#### Key concepts:

```
    Variants:   btn-primary, btn-secondary, etc.
    Sizes:      btn-lg, btn-sm
    States:     disabled, active

```

#### 🧾 2. Cards

Used to display content in a structured box.

#### Example:

```
<div class="card" style="width: 18rem;">
  <div class="card-body">
    <h5 class="card-title">Title</h5>
    <p class="card-text">Some quick content</p>
    <a href="#" class="btn btn-primary">Go</a>
  </div>
</div>
```

Use cases:

- Product UI
- Profile cards
- Blog previews

#### 📝 3. Forms

Collect user input (login, signup, etc.)

#### Example:

```
<input type="email" class="form-control" placeholder="Email">
```

Must know:

- Input types
- Validation (is-valid, is-invalid)
- novalidate usage


#### 🚨 4. Alerts

Used to show messages (success, error, warning)

Example:
```
<div class="alert alert-success">Success!</div>
<div class="alert alert-danger">Error!</div>
```


Features:

- Dismissible alerts
- Contextual colors

#### 🪟 5. Modals

Popup dialogs for user interaction.

Example:
```
<button data-bs-toggle="modal" data-bs-target="#myModal">Open</button>

<div class="modal" id="myModal">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-body">Hello Modal</div>
    </div>
  </div>
</div>
```
Use cases:

- Confirm actions
- Forms in popup
- Login dialog

#### 📊 6. Tables

Display structured data.

Example:
```
<table class="table">
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Sara</td>
    <td>22</td>
  </tr>
</table>
```

Features:

- Striped (table-striped)
- Hover (table-hover)
- Responsive tables

#### 🧭 7. Navbar

Navigation bar for your site.

##### Example:

```
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">MyApp</a>
</nav>
```
Features:

- Responsive menu
- Dropdowns
- Fixed/sticky navbars