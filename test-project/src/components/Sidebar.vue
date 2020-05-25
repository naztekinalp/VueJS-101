<template>
<div class="Sidebar pt-3">
  <h2>Product</h2>
    <aside id="basicSidebar" class="pmd-sidebar">
        <ul class="nav flex-column pmd-sidebar-nav">
            <li class="nav-item">
                    <span class="media-body">Home</span>
            </li>
            <li class="nav-item">
                    <span class="media-body">Inbox</span>
            </li>
            <li class="nav-item">
                    <span class="media-body">Products</span>
            </li>
            <li class="nav-item">
                    <span class="media-body">Invoices</span>
            </li>
            <li class="nav-item">
                    <span class="media-body">Messages</span>
            </li>
            <li class="nav-item">
                    <span class="media-body">Calender</span>
            </li>
            <li class="nav-item">
                    <span class="media-body">Customers</span>
            </li>
            <li class="nav-item">
                    <span class="media-body">Settings</span>
            </li>
        </ul>
    </aside>
</div>
</template>
<script>
export default {
  name: 'SideBar',
  props: {
    msg: String,
  },
};
</script>
<style scoped lang="scss">
.Sidebar{
line-height: 30px;
background-color: #FFFFFF;
float: left;
height:610px;
width:20%;
}
h2{
margin-left:  10px;
  margin-right:  160px;
  font-size: 25;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  color:#172B4D;
}
#basicSidebar{
float: left;
 margin-left: 8px;
}
</style>
