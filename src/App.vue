<template>
  <section>
    <h2>My Friends</h2>
    <ul>
      <li></li>
    </ul>
  </section>
</template>

<script>
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
