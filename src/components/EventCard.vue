<template>
  <div class="event-card">
   <!-- Display Data -->
  </div>
</template>

<script>
export default {
  name: "EventCard",
  // props: {
  //   msg: String
  // }

  data() {
    return {
      event: {
        id: 5928101,
        category: 'animal welfare',
        title: 'Cat Adoption Day',
        desciption: 'Find mister Flabert',
        location: 'Meow Town',
        date: 'January 28, 2022',
        time:'12:00',
        petsAllowed:'true',
        organizer: 'Kat Laydee' 
      }// event
    }
  } // data
}; // export
</script>

<style scoped>
  .event-card {
    padding: 20px;
    width: 250px;
    cursor: pointer;
    border: 1px solid #39495c;
    margin-bottom: 18px;
    border-radius: 15px;
  }

  .event-card:hover {
    transform: scale(1.01);
    box-shadow: 0 3px 12px 0 rgba(0,0,0,0.2);
  }
</style>
