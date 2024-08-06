<template>
      <a href="./about">Back</a>
<div class="container">
    <div class="table-wrapper">
      <table class="table">
        <thead>
          <tr>
            <th scope="col">Name</th>
            <th scope="col">Type</th>
            <th scope="col" colspan="2">Status</th>
            <th scope="col">Assignee</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>John Doe</td>
            <td>IT Support</td>
            <td class="status">Complete</td>
            <td>
              <!-- Button trigger modal -->
              <button
                type="button"
                class="btn"
                data-bs-toggle="modal"
                data-bs-target="#exampleModal"
              >
                View
              </button>
            </td>
            <td>Cheslyn</td>
          </tr>
        </tbody>
        <tbody>
          <tr>
            <td>John Doe</td>
            <td>IT Support</td>
            <td class="statusProgress">In Process</td>
            <td>
              <!-- Button trigger modal -->
              <button
                type="button"
                class="btn"
                data-bs-toggle="modal"
                data-bs-target="#exampleModal"
              >
                View
              </button>
            </td>
            <td>Cheslyn</td>
          </tr>
        </tbody>
        <tbody>
          <tr>
            <td>John Doe</td>
            <td>IT Support</td>
            <td class="statusAssign">To be Assigned</td>
            <td>
              <!-- Button trigger modal -->
              <button
                type="button"
                class="btn"
                data-bs-toggle="modal"
                data-bs-target="#exampleModal"
              >
                View
              </button>
            </td>
            <td>N/A</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>

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
          <h1 class="modal-title fs-5" id="exampleModalLabel">
            Ticket of John Doe
          </h1>
          <button
            type="button"
            class="btn-close"
            data-bs-dismiss="modal"
            aria-label="Close"
          ></button>
        </div>
        <div class="modal-body">Description</div>
        <div class="modal-content">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam nemo
          nostrum at mollitia velit dignissimos adipisci ab? Voluptatum facilis
          assumenda, perferendis recusandae pariatur labore aliquam porro iste
          in rem deleniti. Quia consequatur alias rem accusantium nemo repellat,
          omnis impedit eius maxime labore id doloribus, modi, dolore iste ea
          facere! Cupiditate quibusdam laboriosam ex dignissimos minima ab earum
          iusto reprehenderit libero! Repellat vel libero tenetur neque illum
          officiis maiores sapiente, nostrum error ipsa nemo aut facilis odit,
          maxime quasi rem eos expedita quae commodi vero. Esse autem obcaecati
          praesentium! Fuga, veritatis! Consequatur quod omnis nam, similique,
          vitae hic sit natus harum nihil provident culpa repudiandae at ipsum.
          Cumque, sed vitae nesciunt, soluta repellendus assumenda reiciendis,
          quia enim laborum quasi saepe explicabo. Blanditiis tenetur veniam
          repellendus magni temporibus ducimus voluptatem? Quam hic, qui odit
          delectus quidem deleniti nostrum, laboriosam, eaque nulla modi
          accusantium mollitia eius ea ut aliquam nihil. Sapiente, dicta minima!
        </div>
        <div class="modal-body">Assignee</div>
        <div>Jane Dough</div>
        <div class="modal-body">Comments</div>
        <div>comments to be placed here</div>
        <div class="modal-footer">
          <button
            type="button"
            class="btn"
            data-bs-dismiss="modal"
          >
            Close
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.container {
  display: flex;
  justify-content: center;
  align-items: center;
}

.table-wrapper {
  width: 100%;
}

.table {
  width: 100%;
  margin: 0 auto;
}

.status {
  background-color: greenyellow;
  border-radius: 100px;
  height: 25px;
}

.statusProgress {
  background-color: rgb(255, 196, 47);
  border-radius: 100px;
  height: 25px;
}

.statusAssign {
  background-color: rgb(255, 0, 0);
  border-radius: 100px;
  height: 25px;
}

button {
  border-radius: 50px;
  background-color: rgba(164, 164, 164, 0.225);
  transition: background-color 0.75s ease;
}

button:hover {
  background-color: rgba(164, 164, 164, 0.5);
}

.modal-body {
  font-weight: bold;
}
</style>
