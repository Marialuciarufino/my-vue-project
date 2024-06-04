<template>
  <div class="cart">
    <h2>Meu Carrinho</h2>
    <p>Você ainda não tem itens no seu carrinho.</p>
  </div>
</template>

<script>
export default {
  name: 'AppCart'
};
</script>

<style>
.cart {
  background-color: #f9f9f9;
  border: 1px solid #ddd;
  padding: 20px;
  margin: 20px auto;
  width: 80%;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.cart h2 {
  margin-top: 0;
}

.cart p {
  color: #888;
}
</style>
