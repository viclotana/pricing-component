<template class="cbox">
<div id="mine">
<h1>Available Plans</h1>
<c-grid w="100%" template-columns="repeat(3, 1fr)" gap="6"  >
  <c-box maxW="sm" border-width="1px" rounded="lg" overflow="hidden">
    <c-box p="6">
      <h2>Free Plan</h2>
      <c-divider />
      <c-box
        mt="6"
        mb="6"
        font-weight="semibold"
        as="h3"
        text-align="center"
        line-height="tight"
        is-truncated
      >
        {{ property.title }} <br> 
      </c-box>
      <c-box
      mt="6"
        font-weight="semibold"
        as="h5"
        text-align="center"
        line-height="tight"
        is-truncated>
        {{property.note}}</c-box>
      <c-divider />
      <h2>Apple Music</h2>
      <c-divider />
      <h2>Netflix Family</h2>
      <c-divider />
      <h2>Spotify Family</h2>
      <c-divider />
       <c-box d="flex" align-items="baseline">
        <c-badge rounded="full" px="2" variant-color="green" pl="4" ml="12">
          New
        </c-badge>
        <c-box
          ml="1"
          text-align="center"
        >
         <h2>Amazon Prime</h2> 
        </c-box>
      </c-box>
      <c-divider />
      <c-box pl="12" ml="12">
        Save {{ property.formattedPrice }}
        <c-box as="span" color="gray.600" fontSize="sm" >
          / month
        </c-box>
      </c-box>
      <c-divider />
      <c-box d="flex" mt="2" pl="4" ml="12" align-items="center">
        <c-icon
          v-for="(_, i) in Array(5).fill('')"
          name="star"
          :key="i"
          :color="i < property.rating ? 'green.500' : 'gray.300'"
        />
        <c-box as="span" ml="2" color="gray.600" font-size="sm">
          {{ property.reviewCount }} reviews
        </c-box>
      </c-box>
      <c-divider />
      <c-button-group pl="12" ml="12">
      <c-button ml="6" size="lg" variant-color="gray">Button</c-button>
      </c-button-group>
    </c-box>
  </c-box> 
  <!-- new cards here -->
<c-box maxW="sm" border-width="1px" rounded="lg" overflow="hidden" border="2px" border-radius="md" border-color="grey">
    <c-box p="6">
      <h2>Free Plan</h2>
      <c-divider />
      <c-box
        mt="6"
        mb="6"
        font-weight="semibold"
        as="h3"
        text-align="center"
        line-height="tight"
        is-truncated
      >
        {{ property.title }} <br> 
      </c-box>
      <c-box
      mt="6"
        font-weight="semibold"
        as="h5"
        text-align="center"
        line-height="tight"
        is-truncated>
        {{property.note}}</c-box>
      <c-divider />
      <h2>Apple Music</h2>
      <c-divider />
      <h2>Netflix Family</h2>
      <c-divider />
      <h2>Spotify Family</h2>
      <c-divider />
       <c-box d="flex" align-items="baseline">
        <c-badge rounded="full" px="2" variant-color="green" pl="4" ml="12">
          New
        </c-badge>
        <c-box
          ml="1"
          text-align="center"
        >
         <h2>Amazon Prime</h2> 
        </c-box>
      </c-box>
      <c-divider />
      <c-box pl="12" ml="12">
        Save {{ property.formattedPrice }}
        <c-box as="span" color="gray.600" fontSize="sm" >
          / month
        </c-box>
      </c-box>
      <c-divider />
      <c-box d="flex" mt="2" pl="4" ml="12" align-items="center">
        <c-icon
          v-for="(_, i) in Array(5).fill('')"
          name="star"
          :key="i"
          :color="i < property.rating ? 'green.500' : 'gray.300'"
        />
        <c-box as="span" ml="2" color="gray.600" font-size="sm">
          {{ property.reviewCount }} reviews
        </c-box>
      </c-box>
      <c-divider />
      <c-button-group pl="12" ml="12">
      <c-button ml="6" size="lg" variant-color="green">Button</c-button>
      </c-button-group>
    </c-box>
  </c-box> 
  <!-- new cards here -->
  <c-box maxW="sm" border-width="1px" rounded="lg" overflow="hidden">
    <c-box p="6">
      <h2>Free Plan</h2>
      <c-divider />
      <c-box
        mt="6"
        mb="6"
        font-weight="semibold"
        as="h3"
        text-align="center"
        line-height="tight"
        is-truncated
      >
        {{ property.title }} <br> 
      </c-box>
      <c-box
      mt="6"
        font-weight="semibold"
        as="h5"
        text-align="center"
        line-height="tight"
        is-truncated>
        {{property.note}}</c-box>
      <c-divider />
      <h2>Apple Music</h2>
      <c-divider />
      <h2>Netflix Family</h2>
      <c-divider />
      <h2>Spotify Family</h2>
      <c-divider />
       <c-box d="flex" align-items="baseline">
        <c-badge rounded="full" px="2" variant-color="green" pl="4" ml="12">
          New
        </c-badge>
        <c-box
          ml="1"
          text-align="center"
        >
         <h2>Amazon Prime</h2> 
        </c-box>
      </c-box>
      <c-divider />
      <c-box pl="12" ml="12">
        Save {{ property.formattedPrice }}
        <c-box as="span" color="gray.600" fontSize="sm" >
          / month
        </c-box>
      </c-box>
      <c-divider />
      <c-box d="flex" mt="2" pl="4" ml="12" align-items="center">
        <c-icon
          v-for="(_, i) in Array(5).fill('')"
          name="star"
          :key="i"
          :color="i < property.rating ? 'green.500' : 'gray.300'"
        />
        <c-box as="span" ml="2" color="gray.600" font-size="sm">
          {{ property.reviewCount }} reviews
        </c-box>
      </c-box>
      <c-divider />
      <c-button-group pl="12" ml="12">
      <c-button ml="6" size="lg" variant-color="gray">Button</c-button>
      </c-button-group>
    </c-box>
  </c-box> 
 
</c-grid>
</div>
</template>

<script>
  export default {
    name: 'Example',
    data () {
      return {
        property: {
          title: "$0/month",
          note: "Get a free Apple Music Subscription for 1 year by getting 3 of your friends on the platform.",
          formattedPrice: "$10.00",
          reviewCount: 74,
          rating: 4,
        }
      }
    }
  }
</script>
<style scoped>
#mine {
  margin: 20px;
}

h3, h1 {
  margin: 40px 10px 20px;
  text-align: center;
  font-size: 40px;
}
h2{
  text-align: center;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>