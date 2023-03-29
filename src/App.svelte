<script>
  import svelteLogo from "./assets/svelte.svg";
  import viteLogo from "/vite.svg";
  import Counter from "./lib/Counter.svelte";
  const arr = [
    {
      id: "1",
      name: "Doctors' Appointments",
      description:
        "Full stack application with a Ruby on Rails back-end and a React-Redux front-end. Allows a user to log in and see a list of Doctors, of which they can pick any to make an appointment.",
      extradescription:
        "Full stack application with a Ruby on Rails back-end and a React-Redux front-end. Allows a user to log in and see a list of Doctors, of which they can pick any to make an appointment. Authorized users may add new doctors or delete existing ones",
      featuredimage: "./images/doctors-img.png",
      technologies: ["React", "Redux", "RoR", "PostgreSQL", "Tailwind CSS"],
      liveversion: "https://doctors-reservations.netlify.app",
      source: "https://github.com/asdt560/Doctors-Reservations-Backend",
    },
    {
      id: "2",
      name: "Weather and Pollution Tracker",
      description:
        "A mobile-first application which displays weather data for a list of cities, pulled from the OpenWeather API. It also displays air pollution data for the same.",
      extradescription:
        "A mobile-first application which displays weather data for a list of cities, pulled from the OpenWeather API. It also displays air pollution data for the same. Currently only displays data for a small number of cities, given the amount of requests the API allows and the need to request pollution data for each city individually.",
      featuredimage: "./images/app-pic.PNG",
      technologies: ["React", "Redux", "CSS"],
      liveversion: "https://weather-pollution-tracker-964571.netlify.app/",
      source: "https://github.com/asdt560/weather-metrics-argentina",
    },
    {
      id: "3",
      name: "Space Travelers' Hub",
      description:
        "A React-Redux site that uses data from the SpaceX API to display lists of rockets and missions and allows a user to reserve or join said missions.",
      extradescription:
        "A React-Redux site that uses data from the SpaceX API to display lists of rockets and missions and allows a user to reserve or join said missions. The user can see what missions they have joined and what rockets they have reserved. The user can also cancel their reservations.",
      featuredimage: "./images/spacetravel-img.png",
      technologies: ["React", "Redux", "Bootstrap"],
      liveversion: "https://spacetravelers-justorago-camilovela.netlify.app/",
      source: "https://github.com/asdt560/rocket-mission-list",
    },
    {
      id: "4",
      name: "Cash-Tracker",
      description:
        "A Ruby on Rails application which is designed to allow logged-in users to add and keep track of monetary transactions, creating categories to classify them and then adding them to one or more of them according to what they consider appropriate.",
      extradescription:
        "A Ruby on Rails application which is designed to allow logged-in users to add and keep track of monetary transactions, creating categories to classify them and then adding them to one or more of them according to what they consider appropriate.",
      featuredimage: "./images/cashtracker-img.png",
      technologies: ["RoR", "PostgreSQL", "CSS"],
      liveversion: "https://cash-tracker.onrender.com",
      source: "https://github.com/asdt560/cash-tracker",
    },
  ];
</script>

<main>
  <h1>Justo Rago</h1>

  <div class="card">
    <Counter />
  </div>
</main>

<style>
</style>
