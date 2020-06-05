<template>
    <div class="container">
      <br>
      <div class="row">
        <DevicePage/>
        <div></div>
        <SidePanel/>
      </div>
      
    </div>
</template>

<script>
import DevicePage from './components/Device'
import SidePanel from './components/SidePanel'

export default {
  name: 'app',
  components: {
    DevicePage,
    SidePanel
  }
}
</script>

<style>
.container{
  margin: 50px;
  padding: 50px;
  flex-wrap: wrap;
}

.row{
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;sd
  justify-content: space-between;
  background: grey;
  margin: 10px;
  padding: 10px;
}
</style>
