## Welcome to GitHub Pages


<!doctype html>
<html>
    <head>
        <meta charset="utf-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <script src="https://aframe.io/releases/1.0.4/aframe.min.js"></script>
        <script src="https://unpkg.com/aframe-look-at-component@0.8.0/dist/aframe-look-at-component.min.js"></script>
        <script src="https://raw.githack.com/AR-js-org/AR.js/master/aframe/build/aframe-ar-nft.js"></script>
    </head>

    <body style="margin: 0; overflow: hidden;">
        <a-scene
            embedded
            loading-screen="enabled: false;"
            arjs="sourceType: webcam; debugUIEnabled: false;"
        >
                <a-image
                    src="https://www.pinclipart.com/picdir/middle/204-2042023_transparent-rgba-gradients-clip-art-transparent-download-blue.png"
                    look-at="[gps-camera]"
                    scale="1 1 1"
                    gps-entity-place="latitude: 45.49733379488955; longitude: -348.56476879116605;"
                ></a-image>

            <a-camera gps-camera rotation-reader></a-camera>
        </a-scene>
    </body>
</html>
