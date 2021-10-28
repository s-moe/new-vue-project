<template>
  <section>
    <h2>My Friends</h2>
    <ul>
      <friend-contact></friend-contact>
      <friend-contact></friend-contact>
    </ul>
  </section>
</template>

<script>
import FriendContact from "./components/FriendContact.vue";

export default {
  data() {
    return {
      friends: [
        {
          id: "manuel",
          name: "Manuel Lorenz",
          phone: "012344",
          email: "manuel@localhost.com",
        },
        {
          id: "julie",
          name: "Julie Lorenzo",
          phone: "012344",
          email: "julie@localhost.com",
        },
      ],
    };
  },
};
</script>
