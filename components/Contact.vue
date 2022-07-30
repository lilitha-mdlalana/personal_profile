<template>
  <section id="contact" class="has-text-centered pb-6">
    <h1 class="is-primary is-size-1">Contact Me</h1>
    <div class="is-flex is-flex-direction-row is-justify-content-center">
      <div class="card ml-2 social-card">
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
      <div class="card ml-2 social-card">
        <a href="https://www.github.com/totalgeek-jr">
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
      <div class="card ml-2 social-card">
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
.social-card{
  min-width:300px;
  height: 200px;
}
figure img{
  height:100px;
  width:100px;
}
</style>
