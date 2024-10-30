<script>
export default {
  name: "modal",
  methods: {
    close() {
      this.$emit("close");
    },
  },
};
</script>
<template>
  <div class="modal-backdrop">
    <div class="modal">
      <button type="button" class="btn-closes" @click="close">x</button>
    </div>
  </div>
</template>
<style>
.modal-backdrop {
  position: fixed;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  background-color: rgba(0, 0, 0, 0.3);
  display: flex; 
  justify-content: center;
  align-items: center;
}

.modal {
  background: #ffffff;
  box-shadow: 2px 2px 20px 1px;

  display: flex;
  flex-direction: column;

  width: 300px;
  height: 300px;
  position: relative; 
  border-radius: 8px; 
}

.btn-closes {
  border: none;
  justify-content: end;
  cursor: pointer;
  font-weight: bold;
  color: #4aae9b;
  text-align: end;
  background: white;
  width: 10px;
}
</style>
