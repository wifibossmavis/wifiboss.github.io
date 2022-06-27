# WifibossPH
Registration Details
function init() {
  Tabletop.init( { key: 'https://docs.google.com/spreadsheets/d/e/2PACX-1vRwhEpJoP69E3RUCU2TtFVB2I6h487utJ5jGgnV2Sr6gTu7jiEyRUlE1XcqlJIsewkd-9GgQY35AKg3/pubhtml',
                    callback: function(data, tabletop) { 
                      console.log(data)
                    },
                    simpleSheet: true } )
}
window.addEventListener('DOMContentLoaded', init)
