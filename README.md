# WifibossPH
Registration Details
function init() {
  Tabletop.init( { key: 'https://docs.google.com/spreadsheets/d/1YNjyFaOwBKTZBhnv4w-ePEMV8MpIilUSGEaSnxQbkGs/edit#gid=829480153',
                    callback: function(data, tabletop) { 
                      console.log(data)
                    },
                    simpleSheet: true } )
}
window.addEventListener('DOMContentLoaded', init)
