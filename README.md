# Angular9GoogleMaps


    ng new angular9-google-maps

    require routing y/n?

    Y

    scss 


    cd angular9-google-maps


    ng serve -o


    npm i @agm/core@1.1.0 --save

html

    <div class="layout">
      <div Align="center">
        <h1>Welcome To Agm Core Google Maps</h1>
      </div>

      <div>
        <agm-map [latitude]="lat" [longitude]="lng">
          <agm-marker [latitude]="lat" [longitude]="lng"></agm-marker>
        </agm-map>
      </div>
    </div>
    
    
    
ts

      lat = 51.678418;
      lng = 7.809007;
      
      
scss

    agm-map {
        height: 60vh;
    }

    .layout {
        margin: 50px;
    }
