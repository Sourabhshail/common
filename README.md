useEffect(() => {
if (navigator.geolocation) {
    navigator.permissions
    .query({ name: "geolocation" })
    .then(function (result) {
        console.log(result);
    });
} else {
    console.log("Geolocation is not supported by this browser.");
}
}, []);

