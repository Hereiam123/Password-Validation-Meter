<script>

</script>

<style>
  form {
    --text-color: #afafaf;
    max-width: 500px;
  }

  .field {
    width: 100%;
    position: relative;
    border-bottom: 2px dashed var(--text-color);
    margin: 4rem auto 1rem;
  }

  .label {
    color: var(--text-color);
    font-size: 1.2rem;
  }

  .input {
    outline: none;
    border: none;
    overflow: hidden;
    margin: 0;
    width: 100%;
    padding: 0.25rem 0;
    background: none;
    color: white;
    font-size: 1.2rem;
    font-weight: bold;
  }

  .input:valid {
    color: yellow;
  }

  input:invalid {
    color: red;
  }
</style>

<main>
  <form>
    <div class="field">
      <input type="email" name="email" placeholder="" class="input" />
      <label for="email" class="label">Email</label>
    </div>
    <div class="field">
      <input type="password" name="password" placeholder="" class="input" />
      <label for="password" class="label">Password</label>
    </div>
  </form>
</main>
