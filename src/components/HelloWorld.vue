<script setup>
</script>

<template >
  <div>
    <h1 class="display-4">Loot Tracker</h1>
    <table class="table">
      <thead>
        <tr>
          <th scope="col">item description</th>
          <th scope="col">quantity</th>
          <th scope="col">worth</th>
          <th scope="col">total</th>
          <th scope="col">location</th>
          <th scope="col">date acquired</th>
          <th scope="col">category</th>
          <th scope="col">character</th>
          <th scope="col">vendor price</th>
          <th scope="col">sell?</th>
          <th scope="col">sold?</th>
          <th scope="col">date sold</th>
          <th scope="col">edit</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>diamond</td>
          <td>2</td>
          <td>500</td>
          <td>1000</td>
          <td>aradoon temple</td>
          <td>1/15/2022</td>
          <td>Trade</td>
          <td></td>
          <td>1000</td>
          <td><input type="checkbox" /></td>
          <td><input type="checkbox" /></td>
          <td>1/22/2022</td>
          <td>
            <button
              class="btn btn-sm btn-primary px-3"
              data-bs-toggle="modal"
              data-bs-target="#table-row-edit"
            >
              Edit
            </button>
          </td>
        </tr>
        <tr>
          <td>diamond</td>
          <td>2</td>
          <td>500</td>
          <td>1000</td>
          <td>aradoon temple</td>
          <td>1/15/2022</td>
          <td>Trade</td>
          <td></td>
          <td>1000</td>
          <td><input type="checkbox" /></td>
          <td><input type="checkbox" /></td>
          <td>1/22/2022</td>
          <td>
            <button
              class="btn btn-sm btn-primary px-3"
              data-bs-toggle="modal"
              data-bs-target="#table-row-edit"
            >
              Edit
            </button>
          </td>
        </tr>
        <tr>
          <td>diamond</td>
          <td>2</td>
          <td>500</td>
          <td>1000</td>
          <td>aradoon temple</td>
          <td>1/15/2022</td>
          <td>Trade</td>
          <td></td>
          <td>1000</td>
          <td><input type="checkbox" /></td>
          <td><input type="checkbox" /></td>
          <td>1/22/2022</td>
          <td>
            <button
              class="btn btn-sm btn-primary px-3"
              data-bs-toggle="modal"
              data-bs-target="#table-row-edit"
            >
              Edit
            </button>
          </td>
        </tr>
      </tbody>
    </table>

    <div
      class="modal fade"
      id="table-row-edit"
      tabindex="-1"
      aria-labelledby="table-row-edit-label"
      aria-hidden="true"
    >
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="modal-header">
            <h5 class="modal-title" id="table-row-edit-label">Modal title</h5>
            <button
              type="button"
              class="btn-close"
              data-bs-dismiss="modal"
              aria-label="Close"
            ></button>
          </div>
          <div class="modal-body">...</div>
          <div class="modal-footer">
            <button
              type="button"
              class="btn btn-secondary"
              data-bs-dismiss="modal"
            >
              Close
            </button>
            <button type="button" class="btn btn-primary">Save changes</button>
          </div>
        </div>
      </div>
    </div>
  </div>

</template>

<style lang="scss">
@import "../styles.scss";
</style>

