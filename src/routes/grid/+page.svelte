<script>
    import Grid from 'gridjs-svelte'
    const data = [{
  "id": 1,
  "first_name": "Marlo",
  "last_name": "Weald",
  "email": "mweald0@mtv.com",
  "gender": "Female",
  "ip_address": "126.226.163.158"
}, {
  "id": 2,
  "first_name": "Skylar",
  "last_name": "Darrigone",
  "email": "sdarrigone1@webeden.co.uk",
  "gender": "Male",
  "ip_address": "141.148.13.104"
}, {
  "id": 3,
  "first_name": "Aldridge",
  "last_name": "Jenson",
  "email": "ajenson2@time.com",
  "gender": "Male",
  "ip_address": "58.112.74.236"
}, {
  "id": 4,
  "first_name": "Shawna",
  "last_name": "Vicioso",
  "email": "svicioso3@nba.com",
  "gender": "Female",
  "ip_address": "21.72.43.211"
}, {
  "id": 5,
  "first_name": "Veronique",
  "last_name": "Bagguley",
  "email": "vbagguley4@imgur.com",
  "gender": "Female",
  "ip_address": "177.179.244.62"
}, {
  "id": 6,
  "first_name": "Fraze",
  "last_name": "Thebeau",
  "email": "fthebeau5@seattletimes.com",
  "gender": "Male",
  "ip_address": "101.90.172.155"
}, {
  "id": 7,
  "first_name": "Emmanuel",
  "last_name": "Dawes",
  "email": "edawes6@goodreads.com",
  "gender": "Male",
  "ip_address": "23.187.52.64"
}, {
  "id": 8,
  "first_name": "Hedy",
  "last_name": "Gocke",
  "email": "hgocke7@deviantart.com",
  "gender": "Female",
  "ip_address": "77.173.241.145"
}, {
  "id": 9,
  "first_name": "Laverna",
  "last_name": "Manneville",
  "email": "lmanneville8@abc.net.au",
  "gender": "Female",
  "ip_address": "31.45.199.78"
}, {
  "id": 10,
  "first_name": "Rori",
  "last_name": "Whiscard",
  "email": "rwhiscard9@zdnet.com",
  "gender": "Female",
  "ip_address": "198.98.243.223"
}]


</script>


<Grid search sort pagination={{enabled: true, limit: 5}} {data} />

<style global>
  @import "https://cdn.jsdelivr.net/npm/gridjs/dist/theme/mermaid.min.css";
</style>