<script setup>
import Admin from './components/Admin.vue';
import Calculation from './components/Calculation.vue';
import Card from './components/Card.vue';
import ColorBox from './components/ColorBox.vue';
import FormatName from './components/FormatName.vue';
import ListCourse from './components/ListCourse.vue';
import ManageUser from './components/ManageUser.vue';
import Todo from './components/Todo.vue';
import UserInfor from './components/UserInfor.vue';
import UserLayout from './components/UserLayout.vue';
</script>
<template>
    <div>
      <ListCourse></ListCourse>
      <ColorBox/>
      <Card></Card>
      <Calculation></Calculation>
      <UserInfor></UserInfor>
      <FormatName></FormatName>
      <Admin></Admin>
      <UserLayout></UserLayout>
      <ManageUser></ManageUser>
      <Todo></Todo>
    </div>
</template>

<style>

</style>