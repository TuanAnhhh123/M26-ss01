<script setup>
// import FooterComponent from "./components/FooterComponent.vue";
import Header from "./components/Header.vue";
import FooterComponent from "./components/FooterComponent.vue";
import User from "./components/User.vue";
import Modal from "./components/Modal.vue";
import ListCourse from "./components/ListCourse.vue";
import ColorBox from "./components/ColorBox.vue";
import Card from "./components/Card.vue";
import AdminIndex from "./components/AdminIndex.vue";
import UserLayout from "./components/UserLayout.vue"
import Calulation from "./components/Calulation.vue"
import UserInfo from "./components/UserInfo.vue"
import FormatName from "./components/FormatName.vue"
</script>

<template>
  <div>
    <h1>Hello world</h1>

    <Header></Header>

    <!-- <Header /> -->

    <User />

    <footer-component></footer-component>

    <!-- Modal -->
    <Modal />
    <ListCourse />
    <ColorBox />
    <Card />
    <AdminIndex />
    <UserLayout />
    <Calulation/>
    <UserInfo/>
    <FormatName/>
  </div>
</template>

