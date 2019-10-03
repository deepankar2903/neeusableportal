<template>
  <div id="app">
    <label id="accname">Account Name</label>
    <input id="accname"></input>
    &nbsp;
    &nbsp;
    &nbsp;
    &nbsp;
    <label id="projectid">Project ID</label>
    <input id="projectid"/>
    &nbsp;
    &nbsp;
    &nbsp;
    &nbsp;
    <label id="assettype">Asset Type</label>
    <select id="assettype">
    </select>  
    &nbsp;
    &nbsp;
    &nbsp;
    &nbsp;
    <label id="assetcat">Asset Category</label>
    <select id="assetcat"/><br><br>
    <button id="downloadasset">Download Assets</button>
    <button id="viewreports">View Reports</button><br><br>
    <table>
      <th></th>
      <th>Asset ID</th>
      <th>Asset Title</th>
      <th>Asset Description</th>
      <th>Asset Owner Name</th>
      <th>Asset Status</th>
      <th></th>
      <th></th>
      <tr>
        <td><input type="checkbox"/></td>
        <td>{{assetId}}</td>
        <td>{{assetTitle}}</td>
        <td>{{assetDescp}}</td>
        <td>{{assetowner}}</td>
        <td>{{assetStatus}}</td>
        <td><button>View Details</button></td>
        <td><button>Edit</button></td>
      </tr>
    </table>

  </div>
</template>

<script>

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
table, td, th {
  border: 1px solid black;
}

table {
  border-collapse: collapse;
  width: 100%;
}

th {
  height: 50px;
}
</style>
