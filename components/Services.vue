<script>
export default {
  data() {
    return {
      services: [
        {
          service: 'Design',
          description:
            'My clients get websites and applications that create a positive user experience through superior design.',
          imageUrl: '/design.svg',
          imageDescription: 'Sample description',
        },
        {
          service: 'Website Development',
          description:
            'Because I design using Webflow, I am able to build websites that are fully responsive, compatible with any mobile device, and using semantic code that is clean and easy for my clients to edit. This cuts down on the costs of development.',
          imageUrl: '/webflow.svg',
          imageDescription: 'Sample description',
        },
        {
          service: 'Landing Page',
          description:
            'When it comes to landing pages, I deliver an all-around carefree package. I will design, build and host your site for free. A responsive page optimized for conversions is displayed.',
          imageUrl: '/landing-page.svg',
          imageDescription: 'Sample description',
        },
      ],
    }
  },
}
</script>

<template>
  <section id="services" class="has-text-centered mt-6">
    <h1 class="is-primary is-size-3 is-size-1-tablet">What I do</h1>
    <div class="is-flex-tablet is-flex-direction-row-tablet is-justify-content-center-tablet">
      <MiniCard
        v-for="service in services"
        :key="service.service"
        class="mx-auto my-3 mx-2-tablet "
        :service="service.service"
        :description="service.description"
        :image-path="service.imageUrl"
        :image-description="service.imageDescription"
      />
    </div>
  </section>
</template>
