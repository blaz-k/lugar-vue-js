<template>
  <!--CONTACT START-->
  <div id="contact-section" class="container">
    <div class="row">
      <div class="col-md-6">
        <img src="../assets/img/left.png" alt="" class="img-fluid" />
      </div>
      <div class="col-md-6 contact-right">
        <div class="row g-2">
          <div class="col-md">
            <div class="form-floating">
              <input
                type="text"
                class="form-control"
                id="floatingInputGrid"
                placeholder="First name"
              />
              <label for="floatingTextarea2">First name</label>
            </div>
          </div>
          <div class="col-md">
            <div class="form-floating">
              <input
                type="text"
                class="form-control"
                id="floatingInputGrid"
                placeholder="Last name"
              />
              <label for="floatingTextarea2">Last name</label>
            </div>
          </div>
        </div>
        <div class="row g-2 mt-4">
          <div class="col-md">
            <div class="form-floating">
              <input
                type="email"
                class="form-control"
                id="floatingInputGrid"
                placeholder="email"
              />
              <label for="floatingTextarea2">Email Address</label>
            </div>
          </div>
          <div class="col-md">
            <div class="form-floating">
              <input
                type="text"
                class="form-control"
                id="floatingInputGrid"
                placeholder="Phonenumber"
              />
              <label for="floatingTextarea2">Phone number</label>
            </div>
          </div>
        </div>
        <div class="form-floating mt-4">
          <textarea
            class="form-control"
            placeholder="Leave a comment here"
            id="floatingTextarea2"
            style="height: 100px"
          ></textarea>
          <label for="floatingTextarea2">Description</label>
        </div>
        <button type="button" class="btn btn-dark">Our projects</button>
      </div>
    </div>
  </div>

  <!--CONTACT END-->
</template>

<script>
export default {
  name: "Contact",
};
</script>

<style>
</style>