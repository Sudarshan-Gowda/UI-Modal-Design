# Modal - Onload

To load the modal based on the button click or onClick function.

### Steps to Clone The Repository Application:

1. Download this Project from Git.

```
git clone https://github.com/Sudarshan-Gowda/UI-Modal-Design.git
```

### To Run the Application Locally:

Navigate to the folder modal-onload and open the file index.html with any of the browser.

### Reesult of the App

<img src="https://github.com/Sudarshan-Gowda/UI-Modal-Design/blob/main/modal-onload/docs/Pic01.png"/>

```html
<!-- Button trigger modal -->
<button
  type="button"
  class="btn btn-primary"
  data-bs-toggle="modal"
  data-bs-target="#exampleModal"
>
  Launch demo modal
</button>

<!-- Modal -->
<div
  class="modal fade"
  id="exampleModal"
  tabindex="-1"
  aria-labelledby="exampleModalLabel"
  aria-hidden="true"
>
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
        <button
          type="button"
          class="btn-close"
          data-bs-dismiss="modal"
          aria-label="Close"
        ></button>
      </div>
      <div class="modal-body">...</div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">
          Close
        </button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>
```
