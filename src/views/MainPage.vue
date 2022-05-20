<template>
  <div class="container">
    <section class="structure">
      <div><h1>Students Database</h1>
      <br/>
    </div>
  <div> 
      <form>
        <input placeholder="Student Name"/>
        <input placeholder="Couse"/>
        <input placeholder="Rating"/>
        <button>Add</button>
        <button class = "resetButton">Reset</button>
        <button>Save</button>
        <button class = "resetButton">Cancel</button>
      </form>
  </div>
  <div>
    <TableComponent/>
  </div>
    </section>
  </div>


</template>

<script>
import TableComponent from "../components/TableComponent.vue"

export default {
name: "MainPage",
components: {
  TableComponent
},
setup(){

}
}
</script>

<style>

</style>