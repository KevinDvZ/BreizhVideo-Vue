<template>
<v-simple-table yellow>
  <table id="films">
    <thead>
      <tr>
        <th>ID</th>
        <th>Titre</th>
        <th>Année de sortie</th>
        <th>Description</th>
        <th>Durée </th>
      </tr>
    </thead>
    <tbody>
      <tr v-for="row in rows" v-bind:key="row" v-bind:row="row">
        <td>{{ row.id }}</td>
       
        <td>{{ row.title }}</td>
        <td>{{ row.release_year }}</td>
        <td>{{ row.description }}</td>
        <td> {{ row.length}} </td>
      </tr>
    </tbody>
  </table>
</v-simple-table>
</template>


<style>
#stock {
  margin-left: auto;
  margin-right: auto;
}

table {
  font-family: "Open Sans", sans-serif;
  width: 750px;
  border-collapse: collapse;
  border: 3px solid #44475c;
  margin: 10px 10px 0 10px;
}

table th {
  text-transform: uppercase;
  text-align: left;
  background: #44475c;
  color: #fff;
  padding: 8px;
  min-width: 30px;
}

table td {
  text-align: left;
  padding: 8px;
  border-right: 2px solid #7d82a8;
}
table td:last-child {
  border-right: none;
}
table tbody tr:nth-child(2n) td {
  background: #d4d8f9;
}
</style>

<script>
export default {
    name: "TableauFilms",
     data() {
    return {
        rows :
      [
  {
    "id": 1,
    "title": "ACADEMY DINOSAUR",
    "description": "A Epic Drama of a Feminist And a Mad Scientist who must Battle a Teacher in The Canadian Rockies",
    "release_year": 2006,
    "length": 86
  },
  {
    "id": 2,
    "title": "ACE GOLDFINGER",
    "description": "A Astounding Epistle of a Database Administrator And a Explorer who must Find a Car in Ancient China",
    "release_year": 2006,
    "length": 48
  },
  {
    "id": 3,
    "title": "ADAPTATION HOLES",
    "description": "A Astounding Reflection of a Lumberjack And a Car who must Sink a Lumberjack in A Baloon Factory",
    "release_year": 2006,
    "length": 50
  },
  {
    "id": 4,
    "title": "AFFAIR PREJUDICE",
    "description": "A Fanciful Documentary of a Frisbee And a Lumberjack who must Chase a Monkey in A Shark Tank",
    "release_year": 2006,
    "length": 117
  },
  {
    "id": 5,
    "title": "AFRICAN EGG",
    "description": "A Fast-Paced Documentary of a Pastry Chef And a Dentist who must Pursue a Forensic Psychologist in The Gulf of Mexico",
    "release_year": 2006,
    "length": 130
  },
  {
    "id": 6,
    "title": "AGENT TRUMAN",
    "description": "A Intrepid Panorama of a Robot And a Boy who must Escape a Sumo Wrestler in Ancient China",
    "release_year": 2006,
    "length": 169
  },
  {
    "id": 7,
    "title": "AIRPLANE SIERRA",
    "description": "A Touching Saga of a Hunter And a Butler who must Discover a Butler in A Jet Boat",
    "release_year": 2006,
    "length": 62
  },
  {
    "id": 8,
    "title": "AIRPORT POLLOCK",
    "description": "A Epic Tale of a Moose And a Girl who must Confront a Monkey in Ancient India",
    "release_year": 2006,
    "length": 54
  },
  {
    "id": 9,
    "title": "ALABAMA DEVIL",
    "description": "A Thoughtful Panorama of a Database Administrator And a Mad Scientist who must Outgun a Mad Scientist in A Jet Boat",
    "release_year": 2006,
    "length": 114
  },
  {
    "id": 10,
    "title": "ALADDIN CALENDAR",
    "description": "A Action-Packed Tale of a Man And a Lumberjack who must Reach a Feminist in Ancient China",
    "release_year": 2006,
    "length": 63
  },
  {
    "id": 11,
    "title": "ALAMO VIDEOTAPE",
    "description": "A Boring Epistle of a Butler And a Cat who must Fight a Pastry Chef in A MySQL Convention",
    "release_year": 2006,
    "length": 126
  },
  {
    "id": 12,
    "title": "ALASKA PHANTOM",
    "description": "A Fanciful Saga of a Hunter And a Pastry Chef who must Vanquish a Boy in Australia",
    "release_year": 2006,
    "length": 136
  },
  {
    "id": 13,
    "title": "ALI FOREVER",
    "description": "A Action-Packed Drama of a Dentist And a Crocodile who must Battle a Feminist in The Canadian Rockies",
    "release_year": 2006,
    "length": 150
  },
  {
    "id": 14,
    "title": "ALICE FANTASIA",
    "description": "A Emotional Drama of a A Shark And a Database Administrator who must Vanquish a Pioneer in Soviet Georgia",
    "release_year": 2006,
    "length": 94
  },
  {
    "id": 15,
    "title": "ALIEN CENTER",
    "description": "A Brilliant Drama of a Cat And a Mad Scientist who must Battle a Feminist in A MySQL Convention",
    "release_year": 2006,
    "length": 46
  },
  {
    "id": 16,
    "title": "ALLEY EVOLUTION",
    "description": "A Fast-Paced Drama of a Robot And a Composer who must Battle a Astronaut in New Orleans",
    "release_year": 2006,
    "length": 180
  },
  {
    "id": 17,
    "title": "ALONE TRIP",
    "description": "A Fast-Paced Character Study of a Composer And a Dog who must Outgun a Boat in An Abandoned Fun House",
    "release_year": 2006,
    "length": 82
  },
  {
    "id": 18,
    "title": "ALTER VICTORY",
    "description": "A Thoughtful Drama of a Composer And a Feminist who must Meet a Secret Agent in The Canadian Rockies",
    "release_year": 2006,
    "length": 57
  },
  {
    "id": 19,
    "title": "AMADEUS HOLY",
    "description": "A Emotional Display of a Pioneer And a Technical Writer who must Battle a Man in A Baloon",
    "release_year": 2006,
    "length": 113
  },
  {
    "id": 20,
    "title": "AMELIE HELLFIGHTERS",
    "description": "A Boring Drama of a Woman And a Squirrel who must Conquer a Student in A Baloon",
    "release_year": 2006,
    "length": 79
  }
      ]} }}
     


</script>