<template>
  <div class="mt-5 container">
    <div class="card">
      <div class="card-header">
        <h4>
          Add Student
          <nuxt-link to="/" class="btn btn-danger float-end">Back</nuxt-link>
        </h4>
      </div>

      <div class="card-body">
        <form @submit.prevent="saveStudent">
          <div class="mb-3">
            <label>Name</label>
            <input type="text" class="form-control" v-model="students.name" />
          </div>
          <div class="mb-3">
            <label>Course</label>
            <input type="text" class="form-control" v-model="students.course" />
          </div>
          <div class="mb-3">
            <label>Email</label>
            <input type="text" class="form-control" v-model="students.email" />
          </div>
          <div class="mb-3">
            <label>Phone</label>
            <input type="text" class="form-control" v-model="students.phone" />
          </div>
          <div class="mb-3">
            <button type="submit" class="btn btn-primary">Save</button>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "studentCreate",
  data() {
    return {
      students: {
        name: "",
        course: "",
        email: "",
        phone: "",
      },
    };
  },
  methods: {
    saveStudent() {
      alert("am here");
    },
  },
};
</script>

<style></style>
