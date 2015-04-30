# Responsive slideshow Web Component

Such component was tested with FF 36.0.4 and Chromium 41.0.2272.76 under ubuntu 64 bit

## Usage

Html code

    <!DOCTYPE html>
    <html>
        <head>
            <!-- 1. Load platform support before any code that touches the DOM. -->
            <script src="/path/to/bower_components/webcomponentsjs/webcomponents.min.js"></script>
            <!-- 2. Load the component using an HTML Import -->
            <link rel="import" href="/path/to/abidibo-slideshow.html">
        </head>
        <body>
            <!-- 3. Declare the element by its tag. -->
            <div>
                <abidibo-slideshow>
                    <img src="img/670-1.jpg" alt="img-1" />
                    <img src="img/670-2.jpg" alt="img-2" />
                    <img src="img/670-3.jpg" alt="img-3" />
                </abidibo-slideshow>
            </div>
        </body>
    </html>
