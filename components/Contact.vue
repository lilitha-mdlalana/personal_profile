<template>
  <section id="contact" class="has-text-centered pb-6">
    <h1 class="is-primary is-size-2 is-size-1-tablet">Contact Me</h1>
    <div class="flex">
      <div class="card social-card mx-2 my-3 mx-1-tablet">
        <a href="https://twitter.com/techDevLitha">
          <div class="card-content">
            <div class="content">
              <figure>
                <img src="/twitter.png" alt="Twitter link to TechDevLitha" />
              </figure>
              <p>Twitter</p>
            </div>
          </div>
        </a>
      </div>
      <div class="card social-card mx-2 my-3 mx-1-tablet">
        <a href="https://www.github.com/lilitha-mdlalana">
          <div class="card-content">
            <div class="content">
              <figure>
                <img src="/github.png" alt="Github image" />
              </figure>
              <p>Github</p>
            </div>
          </div>
        </a>
      </div>
      <div class="card social-card mx-2 my-3 mx-1-tablet">
        <a href="mailto:innomdlalana@gmail.com">
          <div class="card-content">
            <div class="content">
              <figure>
                <img src="/email.svg" alt="email" />
              </figure>
              <p>Email</p>
            </div>
          </div>
        </a>
      </div>
    </div>
  </section>
</template>

<style scoped>
.social-card {
  min-width: 18.75rem;
  height: 12, 5rem;
}
figure img {
  height: 6.25rem;
  width: 6.25rem;
}
@media screen and (min-width: 768px) {
  .flex {
    display: flex;
    justify-content: center;
  }
}
@media screen and (max-width: 768px) {
  .social-card {
    min-width: 9.5rem;
    height: 12.5rem;
  }
}
</style>
