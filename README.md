# WifibossPH
Registration Details
function init() {
          Papa.parse('https://docs.google.com/spreadsheets/d/1YNjyFaOwBKTZBhnv4w-ePEMV8MpIilUSGEaSnxQbkGs/edit#gid=829480153', {
          download: true,
          header: true,
          complete: function(results) {
            var data = results.data
            console.log(data)
          }
        })
window.addEventListener('DOMContentLoaded', init)
