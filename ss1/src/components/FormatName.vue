<template>
  <div>
    <h2>Họ và tên: {{ formatName(user) }}</h2>
  </div>
</template>
<script>
export default {
  name: 'FormatName',
  data() {
    return {
      user: {
        firstName: 'Nguyễn Văn',
        lastName: 'Nam'
      }
    };
  },
  methods: {
    formatName(user) {
      return `${user.firstName} ${user.lastName}`;
    }
  }
}
</script>