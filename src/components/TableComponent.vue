<template>
  <section>
    <div class='tbl-header'>
      <table cellpadding='0' cellspacing='0' border='0'>
        <thead>
          <tr>
            <th>Name</th>
            <th>Course</th>
            <th>Rating</th>
            <th>Actions</th>
          </tr>
        </thead>
      </table>
    </div>
    <div class='tbl-content'>
      <table cellpadding='0' cellspacing='0' border='0'>
        <tbody>
          <tr>
            <td>Estudante 1</td>
            <td>Administração</td>
            <td>9</td>
            <td>
              <button class='editButton'>Edit</button>
              <button class='deleteButton'>Delete</button>
            </td>
          </tr>
        </tbody>
      </table>
    </div>
  </section>
  <div>
    <br/>
    <h2>Ops, no data found :(</h2>
  </div>

</template>

<script>
export default {
  name: "TableComponent",
  props:{},
  emits:[],
  setup(){}

}
</script>

<style>

</style>