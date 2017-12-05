<template>
  <svg :width="width" :height="height" viewBox="0 0 24 32" style="fill: #3B444F">
    <title>kono</title>
    <path d="M1.967 0h7.845v31.846h-7.845c-1.086 0-1.967-0.88-1.967-1.967v-27.913c0-1.086 0.88-1.967 1.967-1.967zM10.496 17.148h8.872c0.841 0 1.588 0.534 1.861 1.33l3.686 10.765c0.352 1.028-0.196 2.146-1.224 2.498-0.205 0.070-0.42 0.106-0.637 0.106h-6.12c-0.841 0-1.588-0.534-1.861-1.33l-4.577-13.369z"></path>
    <defs>  
      <linearGradient id="logo-gradient" x1="50%" y1="0%" x2="50%" y2="100%" > 
        <stop offset="0%" stop-color="#00c6fb">
          <animate attributeName="stop-color" values="#00c6fb; #005bea; #00c6fb" dur="4s" repeatCount="indefinite"></animate>
        </stop>
        <stop offset="100%" stop-color="#005bea">
          <animate attributeName="stop-color" values="#005bea; #00c6fb; #005bea" dur="4s" repeatCount="indefinite"></animate>
        </stop>
      </linearGradient> 
    </defs>
    <g id="circle-in-logo">
      <path fill="url('#logo-gradient')" d="M16.182 5.879h0.012c2.706 0 4.899 2.194 4.899 4.899v0c0 2.706-2.194 4.899-4.899 4.899h-0.012c-2.706 0-4.899-2.194-4.899-4.899v0c0-2.706 2.194-4.899 4.899-4.899z"></path>
    </g>
  </svg>
</template>
<script>
export default {
  name: 'kono-logo',
  props: {
    width: {
      type: Number,
      required: true
    },
    height: {
      type: Number,
      required: true
    }
  },
  name: 'logo'
}
</script>
background-image: linear-gradient(to top, #00c6fb 0%, #005bea 100%);6f86d6
