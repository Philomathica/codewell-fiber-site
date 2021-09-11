<nav>
  <div class="title">Fiber</div>
  <div>
    <ul>
      <li><a href="/">Community</a></li>
      <li><a href="/">Pricing</a></li>
      <li><a href="/">Features</a></li>
    </ul>
  </div>
  <div>
    <button>Sign in</button>
    <button class="active">Sign Up</button>
  </div>
</nav>

<style lang="scss">
  nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: 1.4rem;
  }

  ul {
    display: flex;
    gap: 1rem;
    list-style-type: none;
    font-weight: var(--font-weight-light);
  }

  a {
    color: var(--color-black);
    text-decoration: none;
  }

  button {
    padding: 1.5rem;
    border-radius: 0.5rem;
    font-weight: var(--font-weight-bold);
    border: none;
    background-color: transparent;

    &:hover {
      cursor: pointer;
      background-color:  var(--color-primary-light);;
    }
  }

  .active {
    background-color: var(--color-primary);
    color: var(--color-white);
  }

  .title {
    font-weight: var(--font-weight-bold);
  }
</style>
