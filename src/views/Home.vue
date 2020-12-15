<template>
  <div class="events">
    <img alt="Vue logo" src="../assets/logo.png" />
    <EventCard v-for="event in events" :key="event.id" :event="event"/>
  </div>
</template>

<script>
// @ is an alias to /src
import EventCard from "@/components/EventCard.vue";

export default {
  name: "Home",
  components: {
    EventCard
  },
  data() {
    return {
      events: [
{
        id: 5928101,
        category: 'animal welfare 1',
        title: 'Cat Adoption Day',
        desciption: 'Find mister Flabert',
        location: 'Meow Town',
        date: 'January 28, 2022',
        time:'12:00',
        petsAllowed:'true',
        organizer: 'Kat Laydee' 
      },// event
        {
        id: 5928102,
        category: 'animal welfare 2',
        title: 'Cat Adoption Day',
        desciption: 'Find mister Flabert',
        location: 'Meow Town',
        date: 'January 28, 2022',
        time:'12:00',
        petsAllowed:'true',
        organizer: 'Kat Laydee' 
      },// event
       {
        id: 5928105,
        category: 'animal welfare 3',
        title: 'Cat Adoption Day',
        desciption: 'Find mister Flabert',
        location: 'Meow Town',
        date: 'January 28, 2022',
        time:'12:00',
        petsAllowed:'true',
        organizer: 'Kat Laydee' 
      },// event
       {
        id: 5928104,
        category: 'animal welfare 4',
        title: 'Cat Adoption Day',
        desciption: 'Find mister Flabert',
        location: 'Meow Town',
        date: 'January 28, 2022',
        time:'12:00',
        petsAllowed:'true',
        organizer: 'Kat Laydee' 
      }// event
      ]
    }
  } // data
};
</script>

<style scoped>
  .events {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
</style>
