# Interactive Js Map of Nepal
- Lightweight Js Plugin

![jsmap](https://raw.githubusercontent.com/a-M-i-T/interactive-js-map-nepal/main/interactive-js-map.gif)

# Usage

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>

    <script type="text/javascript">
    	$('#loadMap').initMap({
            data: [
                { province: 'Koshi', population: 1000000 },
                { province: 'Madhesh', population: 1500000 },
                { province: 'Bagmati', population: 1200000 },
                { province: 'Gandaki', population: 900000 },
                { province: 'Lumbini', population: 800000 },
                { province: 'Karnali', population: 600000 },
                { province: 'Sudurpashchim', population: 500000 }
            ],
            interval: 2000
        });
    </script>
