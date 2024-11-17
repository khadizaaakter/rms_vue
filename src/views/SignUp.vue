<template>
  <div class="container text-center mt-12">
    <div class="card shadow-lg p-4 mx-auto" style="max-width: 400px">
      <h1 class="mb-4">Sign Up</h1>
      <form>
        <div class="mb-3">
          <input
            type="text"
            class="form-control"
            placeholder="Enter your name"
            required
          />
        </div>
        <div class="mb-3">
          <input
            type="email"
            class="form-control"
            placeholder="Enter your email"
            required
          />
        </div>
        <div class="mb-3">
          <input
            type="password"
            class="form-control"
            placeholder="Enter your password"
            required
          />
        </div>
        <button type="submit" class="btn btn-primary w-100">Sign Up</button>
        <div class="last-button d-flex">
          <p class="text-secondary mt-3">Don't have an account?</p>
          <button class="btn btn-link">Sign in</button>
        </div>
      </form>
    </div>
  </div>
</template>
<script>
export default {
  name: "SignUp",
};
</script>
<style></style>
