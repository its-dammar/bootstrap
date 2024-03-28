Core Coding: HTML, CSS, SCSS, JavaScript

Bootstrap: Frontend Framework of CSS
            : Fast Development
            : predefine components, funcanality

Uses:
Class based

botostrap: 

1. Connection | setup
go to bootstrap official website and copy the following links
<!-- css link -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous">


<!-- javascript link -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4" crossorigin="anonymous"></script>

2. Classes
     color:

     primary
     secondary
     success
     danger
     dark
     info
     light
     warning

     Text color
     color:red;
     b5:
     text-primary

     background-color:red;
     b5:
     bg-primary

     shadow: 1px 2px 3px red;
     b5:
     shadow-sm
     shadow
     shadow-lg

     border-radius:40px;
     b5:
     rounded
     rounded-circle
     rounded-pill
     rounded-0 to rounded-5

     Width:100%;
     b5:
    <!-- 100% -->
     w-100
     w-75
     w-50
     w-25

     height:100vh | 100%;
     b5:
     <!-- 100% -->
     h-100
     h-75
     h-50
     h-25

     eg
     <div style="height:500px">
        <h1 class="bg-info h-25">Lorem ipsum dolor sit amet.</h1>
    </div>

    position: relative;
    b5:
    position-relative
    position-absolute
    position-sticky
    position-static

    <!-- 100% -->
    top-100
    top-50

    bottom-50

    start-100  (left)

    end-100   (right)


    line-height: 2;
    b5:
    lh-2

    Font-size: 2px;
    b5:
    fs-1    (big font)
    to 
    fs-6    (small)

    text-decoration:none | underline | overline | justify;
    b5:
    text-center
    text-underline

    button
    b5:
    btn
    btn btn-primary
    btn btn-outline-primary
    btn-sm
    btn-lg

    images:
    b5:
    img-fluid           (carousel: slider  -> width:100%, height:300px)
    img-thumbnails       (200*200)


    overflow: hidden | visible | none;
    b5:
    overflow-hidden


    Box Model: content, padding, margin, border
    Margin:
    margin: 2px;
    b5:
    m-5 (margin:48px)
    mt-5 (margin top)
    mb-5 (margin bottom)
    ms-5  (margin left)
    me-5  (margin-right)
    my-5 ( margin top and bottom)
    mx-5  (margin right left)

    padding:
    padding: 2px;
    b5:
    p-5 (padding:48px)
    pt-5 (padding top)
    pb-5 (padding bottom)
    ps-5  (padding left)
    pe-5  (padding-right)
    py-5 ( padding top and bottom)
    px-5  (padding right left)


    display: inline;
    b5:
    d-inline
    d-block
    d-inline-block

    flaot:left;
    b5:
    float-start
    float-end

    d-flex                  (display:flex)
    flex-grow-1             (flex-grow:1)
    flex-shring-1
    flex-row                (flex-direction:row)
    flex-wrap               (flex-wrap:wrap)
    g-5                     (gap:30px)
    justify-content-between (justify-content: space-between)
    justify-content-around  (justify-content: space-around)
    justify-content-evenly  (justify-content: space-evenly)
    justify-content-start   (justify-content: start)
    justify-content-center  (justify-content: center)
    justify-content-end     (justify-content: end)
    align-items-center      (align-items:center)
    align-items-start       (align-items:top)
    align-items-end         (align-items:bottom)

    opacity:1;  (total value of the opacity is 1)
    b5:
    opacity-100
    opacity-75
    opacity-50
    opacity-25


    border: 1px solid red;
    b5:
    border
    border border-primary
    border border-primary border-0  (border-0 to border-5)
    border-primary border-5 border-top  


    table:
    <div class="table-responsive">
        <table class="table">

        </table>
    </div>

    table-responsive  (parent element of table element)
    table               (on table element)
    table table-bordered
    table table-hover
    table table-primary
    table table-striped


    Form:
    form-label      (label element)
    form-control    (input element)


    container           (design center layout)
    container-fluid     (full width layout)

    
    Responsive Layout: (flex box | column layout )

    row  (provide "row" class to the parent element)
       col (col provide "col" class to the child element)

    total column: 12

    Break point:
    classes
     -      <576        smallest devices  (480x)
    sm      >576        small device       (600px)  android | IOS
    md      768         medium              tablet                      
    lg      992         large device        laptop       
    xl      1200        extra large         desktop
    xxl     1400        extra extra lage    extra large device

    









    






