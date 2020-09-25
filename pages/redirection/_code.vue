<template>
  <div>
    Refresh the page with F5. There must be no redirection. But there is, if there is a space or a non-ASCII character in the URL.
  </div>
</template>

<script>
export default {
  asyncData({ redirect, route }) {
    if (process.server) {
      // Redirect to the same route
      redirect(route);
    }

    return {};
  }
}
</script>