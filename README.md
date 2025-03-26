<!DOCTYPE html>
<html>
<head>
    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://netdna.bootstrapcdn.com/bootstrap/3.0.0/css/bootstrap-glyphicons.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.2.0/css/all.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css"/>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_4173d0410d75dc81d269b1a032660cac {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
                .leaflet-container { font-size: 1rem; }
            </style>
        
</head>
<body>
    
    
<div style="
    position: fixed;
    top: 80px;
    right: 30px;
    max-height: 80%;
    overflow-y: auto;
    padding: 15px;
    border: 1px solid #ccc;
    background-color: white;
    border-radius: 8px;
    box-shadow: 2px 2px 5px rgba(0,0,0,0.2);
    font-family: sans-serif;
    z-index: 9999;
    width: 260px;
">
    <h4 style="margin-top: 0; font-weight: bold;">Route Legend</h4>
    <hr style="margin-top: 4px; margin-bottom: 12px; border: none; border-top: 2px solid #888;">
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#496E6E; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">1 HIGHWAY 7</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#66A6BC; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">10 WOODBRIDGE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#6DC069; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">105 DUFFERIN</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#00B547; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">107 KEELE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#00B547; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">10702 KEELE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#6DC069; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">12 PINE VALLEY</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A17D7D; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">13 ISLINGTON</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#66A6BC; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">14 14TH AVENUE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#4B6CB4; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">16 16TH AVENUE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#C4A006; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">165 WESTON</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#6DC069; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">18 BUR OAK</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#C4A006; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">2 MILLIKEN</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#806A50; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">20 JANE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#00838B; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">21 VELLORE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#F58220; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">23 THORNHILL WOODS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#00AEEF; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">24 WOODBINE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#BD5B5E; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">25 MAJOR MACKENZIE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#3EC7F4; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">26 MAPLE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A54686; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">3 THORNHILL</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#8B0030; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">300 BUSINESS EXPRESS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#0079C1; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">301 MARKHAM EXPRESS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#00B5CC; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">302 UNIONVILLE EXPRESS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#702D03; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">303 BUR OAK EXPRESS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#4C7520; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">304 MOUNT JOY EXPRESS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A3248F; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">305 BOX GROVE EXPRESS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#0058A9; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">32 AURORA SOUTH</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A3248F; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">320 JANE EXPRESS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#00B5CC; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">33 WELLINGTON - LESLIE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A3248F; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">360 VAUGHAN MILLS / WONDERLAND</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A3248F; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">361 NASHVILLE EXPRESS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A3248F; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">391 BAYVIEW EXPRESS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#0058A9; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">4 MAJOR MACKENZIE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#806A50; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">40 UNIONVILLE LOCAL</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">401 ST BROTHER ANDRE SS VIA BOX GROVE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">402 BUR OAK / PIERRE ELLIOTT TRUDEAU SS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A3248F; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">403 ST BROTHER ANDRE SS VIA RAYMERVILLE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A3248F; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">404 MARKVILLE SS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">405 ST AUGUSTINE SS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">406 MARKHAM DISTRICT SS VIA BUR OAK</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A3248F; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">408 OUR LADY QUEEN OF THE WORLD SS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">410 MARKHAM DISTRICT SS VIA CARLTON</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">411 MARKHAM DISTRICT SS VIA BOX GROVE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">412 THORNLEA SS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">413 ST ROBERT SS VIA JOHN</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A3248F; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">414 ST KATHARINE DREXEL SS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">415 STOUFFVILLE DISTRICT SS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">416 MARKHAM DISTRICT SS VIA NINTH LINE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#636569; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">417 BILL HOGARTH SS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">418 PIERRE ELLIOTT TRUDEAU SS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">420 NEWMARKET SS VIA SAVAGE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">423 NEWMARKET SS VIA BRISTOL</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">424 KESWICK SS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">425 HURON HEIGHTS SS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">426 DR G.W. WILLIAMS SS VIA HOLLIDGE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">427 SACRED HEART SS VIA STONEHAVEN</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">428 DR G.W. WILLIAMS SS VIA HENDERSON</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">429 CARDINAL CARTER / AURORA SS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">430 SACRED HEART SS VIA MAIN</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">432 AURORA SS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A3248F; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">433 CARDINAL CARTER SS VIA KINGSHILL</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A3248F; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">434 CARDINAL CARTER SS VIA WELLINGTON</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A3248F; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">436 CARDINAL CARTER SS VIA PARKER</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A3248F; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">437 ST MAXIMILIAN KOLBE SS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#66A6BC; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">44 BRISTOL</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">440 ST THERESA SS VIA MILL</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">442 RICHMOND HILL SS VIA GAMBLE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">443 LANGSTAFF SS VIA SHAFTSBURY</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">444 LANGSTAFF SS VIA VALLEYMEDE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">445 ST ROBERT SS VIA SPADINA</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">446 ST THERESA SS VIA MCCALLUM</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">447 ST THERESA SS VIA JEFFERSON FOREST</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">448 RICHMOND HILL SS VIA VALLEYMEDE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">449 RICHMOND GREEN SS VIA HILLMOUNT</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">450 ST THERESA SS VIA TOWER HILL</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">452 RICHMOND GREEN SS VIA HAZELTON</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">460 HOLY CROSS SS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">461 EMILY CARR SS VIA ROYALPARK</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">462 MAPLE SS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">464 ST JOAN OF ARC SS VIA AMERICA</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">465 ST JOAN OF ARC SS VIA MELVILLE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#626469; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">466 TOMMY DOUGLAS SS VIA FOSSIL HILL</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A3248F; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">467 TOMMY DOUGLAS SS VIA CITYVIEW</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A3248F; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">468 EMILY CARR SS VIA KLEINBURG</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A3248F; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">469 FATHER BRESSANI SS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A3248F; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">470 WESTMOUNT SS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A3248F; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">471 STEPHEN LEWIS SS VIA TEN OAKS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A3248F; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">473 STEPHEN LEWIS SS VIA THOMAS COOK</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#496E6E; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">5 CLARK</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#684287; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">50 QUEENSWAY</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#DC62A5; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">51 KESWICK</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A54686; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">52 HOLLAND LANDING</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#F28AB2; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">522 MARKHAM LOCAL</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#806A50; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">54 BAYVIEW</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#0058A9; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">55 DAVIS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#FBB034; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">56 GORHAM - EAGLE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#00AEEF; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">57 MULOCK</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#009CDB; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">601 VIVA BLUE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A3248F; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">60102 VIVA BLUE B</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#9461A8; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">603 VIVA PURPLE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A3248F; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">60301 VIVA PURPLE A</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#FBAF33; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">605 VIVA ORANGE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#FFDD00; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">607 VIVA YELLOW</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#0058A9; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">7 MARTIN GROVE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#00AEEF; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">77 HIGHWAY 7</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#2A2A86; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">8 KENNEDY</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#F37053; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">80 ELGIN MILLS</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#806A50; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">81 INSPIRATION</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#0095DA; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">82 VALLEYMEDE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#72BF44; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">83 TRENCH</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#72BF44; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">8301 TRENCH</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A3238E; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">85 RUTHERFORD</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#B72055; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">86 NEWKIRK - RED MAPLE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#C4A006; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">87 AUTUMN HILL</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#00A88E; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">88 BATHURST</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#F58220; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">9 NINTH LINE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#F58220; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">90 LESLIE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#F58220; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">9002 LESLIE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A37C53; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">91 BAYVIEW</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A37C53; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">9101 BAYVIEW</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#A37C53; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">9102 BAYVIEW</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#496E6E; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">96 KEELE - YONGE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#007647; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">98 YONGE</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#007647; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">9899 YONGE (LATE NIGHT)</div>
    </div>
    
    <div style="display: flex; align-items: center; margin-bottom: 6px;">
        <div style="background:#684287; width:14px; height:14px; margin-right:10px; border:1px solid #000;"></div>
        <div style="font-size:12px;">99 YONGE</div>
    </div>
    
</div>
    
            <div class="folium-map" id="map_4173d0410d75dc81d269b1a032660cac" ></div>
        
</body>
<script>
    
    
            var map_4173d0410d75dc81d269b1a032660cac = L.map(
                "map_4173d0410d75dc81d269b1a032660cac",
                {
                    center: [43.7, -79.42],
                    crs: L.CRS.EPSG3857,
                    ...{
  "zoom": 10,
  "zoomControl": true,
  "preferCanvas": false,
}

                }
            );

            

        
    
            var tile_layer_9ba870618c523e8001c4def1b6cebcd4 = L.tileLayer(
                "https://tile.openstreetmap.org/{z}/{x}/{y}.png",
                {
  "minZoom": 0,
  "maxZoom": 19,
  "maxNativeZoom": 19,
  "noWrap": false,
  "attribution": "\u0026copy; \u003ca href=\"https://www.openstreetmap.org/copyright\"\u003eOpenStreetMap\u003c/a\u003e contributors",
  "subdomains": "abc",
  "detectRetina": false,
  "tms": false,
  "opacity": 1,
}

            );
        
    
            tile_layer_9ba870618c523e8001c4def1b6cebcd4.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_cf5c98c325f07ed380f588c95d5b7df6_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#496E6E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_cf5c98c325f07ed380f588c95d5b7df6_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_cf5c98c325f07ed380f588c95d5b7df6 = L.geoJson(null, {
                onEachFeature: geo_json_cf5c98c325f07ed380f588c95d5b7df6_onEachFeature,
            
                style: geo_json_cf5c98c325f07ed380f588c95d5b7df6_styler,
            ...{
}
        });

        function geo_json_cf5c98c325f07ed380f588c95d5b7df6_add (data) {
            geo_json_cf5c98c325f07ed380f588c95d5b7df6
                .addData(data);
        }
            geo_json_cf5c98c325f07ed380f588c95d5b7df6_add({"features": [{"geometry": {"coordinates": [[-79.425239, 43.839817], [-79.429968, 43.841201], [-79.423364, 43.841807], [-79.420176, 43.842451], [-79.416696, 43.842623], [-79.415058, 43.842757], [-79.411367, 43.843923], [-79.408165, 43.844946], [-79.405542, 43.840071], [-79.398532, 43.840513], [-79.39534, 43.841219], [-79.392058, 43.841994], [-79.3896, 43.842582], [-79.386826, 43.843161], [-79.382711, 43.84415], [-79.37832, 43.845217], [-79.364532, 43.848339], [-79.361786, 43.848961], [-79.35845, 43.849538], [-79.352661, 43.850916], [-79.346305, 43.852215], [-79.339497, 43.853825], [-79.332889, 43.855795], [-79.329443, 43.856665], [-79.324775, 43.857719], [-79.323604, 43.857991], [-79.315239, 43.859959], [-79.30894, 43.861433], [-79.302829, 43.862761], [-79.298558, 43.863806], [-79.292103, 43.865302], [-79.288545, 43.866113], [-79.283868, 43.867217], [-79.277746, 43.868842], [-79.272473, 43.870105], [-79.267082, 43.871371], [-79.264292, 43.872027], [-79.259326, 43.873945], [-79.257238, 43.874455], [-79.250125, 43.876169], [-79.243483, 43.87771], [-79.238146, 43.878932], [-79.235156, 43.880494], [-79.23182, 43.881109], [-79.235961, 43.883962], [-79.23433, 43.884453], [-79.229955, 43.885504], [-79.229063, 43.884952], [-79.223503, 43.883597], [-79.221315, 43.884136], [-79.220416, 43.882328], [-79.214597, 43.88235], [-79.212785, 43.869092], [-79.215888, 43.869834], [-79.220643, 43.870852], [-79.224298, 43.870037], [-79.228283, 43.867323], [-79.229206, 43.865536], [-79.230636, 43.865957], [-79.232671, 43.868936], [-79.23386, 43.875474], [-79.234601, 43.878512], [-79.229019, 43.878971], [-79.225589, 43.880425], [-79.227727, 43.884372], [-79.230203, 43.885522], [-79.233171, 43.884872], [-79.234428, 43.884572], [-79.231791, 43.880698]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_cf5c98c325f07ed380f588c95d5b7df6.bindTooltip(
                `<div>
                     1 HIGHWAY 7
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_cf5c98c325f07ed380f588c95d5b7df6.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_c702b4c8b94941b4578926c08b549704_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#496E6E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_c702b4c8b94941b4578926c08b549704_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_c702b4c8b94941b4578926c08b549704 = L.geoJson(null, {
                onEachFeature: geo_json_c702b4c8b94941b4578926c08b549704_onEachFeature,
            
                style: geo_json_c702b4c8b94941b4578926c08b549704_styler,
            ...{
}
        });

        function geo_json_c702b4c8b94941b4578926c08b549704_add (data) {
            geo_json_c702b4c8b94941b4578926c08b549704
                .addData(data);
        }
            geo_json_c702b4c8b94941b4578926c08b549704_add({"features": [{"geometry": {"coordinates": [[-79.361105, 43.84881], [-79.35845, 43.849538], [-79.352661, 43.850916], [-79.346305, 43.852215], [-79.339497, 43.853825], [-79.332889, 43.855795], [-79.329443, 43.856665], [-79.324775, 43.857719], [-79.323604, 43.857991], [-79.315239, 43.859959], [-79.30894, 43.861433], [-79.302829, 43.862761], [-79.298558, 43.863806], [-79.292103, 43.865302], [-79.288545, 43.866113], [-79.283868, 43.867217], [-79.277746, 43.868842], [-79.272473, 43.870105], [-79.267082, 43.871371], [-79.264292, 43.872027], [-79.259326, 43.873945], [-79.257238, 43.874455], [-79.250125, 43.876169], [-79.243483, 43.87771], [-79.238146, 43.878932], [-79.235156, 43.880494], [-79.23182, 43.881109], [-79.235961, 43.883962], [-79.23433, 43.884453], [-79.229955, 43.885504], [-79.229063, 43.884952], [-79.223503, 43.883597], [-79.221315, 43.884136], [-79.220416, 43.882328], [-79.214597, 43.88235], [-79.212785, 43.869092], [-79.215888, 43.869834], [-79.220643, 43.870852], [-79.224298, 43.870037], [-79.228283, 43.867323], [-79.229206, 43.865536], [-79.230636, 43.865957], [-79.232671, 43.868936], [-79.23386, 43.875474], [-79.234601, 43.878512], [-79.229019, 43.878971], [-79.225589, 43.880425], [-79.227727, 43.884372], [-79.230203, 43.885522], [-79.233171, 43.884872], [-79.234428, 43.884572], [-79.231791, 43.880698]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_c702b4c8b94941b4578926c08b549704.bindTooltip(
                `<div>
                     1 HIGHWAY 7
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_c702b4c8b94941b4578926c08b549704.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_f8dbaaebef7cfa9d856720d9fd5c723d_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#496E6E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_f8dbaaebef7cfa9d856720d9fd5c723d_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_f8dbaaebef7cfa9d856720d9fd5c723d = L.geoJson(null, {
                onEachFeature: geo_json_f8dbaaebef7cfa9d856720d9fd5c723d_onEachFeature,
            
                style: geo_json_f8dbaaebef7cfa9d856720d9fd5c723d_styler,
            ...{
}
        });

        function geo_json_f8dbaaebef7cfa9d856720d9fd5c723d_add (data) {
            geo_json_f8dbaaebef7cfa9d856720d9fd5c723d
                .addData(data);
        }
            geo_json_f8dbaaebef7cfa9d856720d9fd5c723d_add({"features": [{"geometry": {"coordinates": [[-79.231791, 43.880698], [-79.235086, 43.879252], [-79.239105, 43.878894], [-79.243027, 43.877991], [-79.249734, 43.876414], [-79.257009, 43.874718], [-79.260273, 43.873906], [-79.26482, 43.872073], [-79.267589, 43.871474], [-79.271936, 43.870427], [-79.27729, 43.869189], [-79.285212, 43.86708], [-79.288041, 43.866433], [-79.292544, 43.865408], [-79.29815, 43.864113], [-79.304799, 43.862602], [-79.30933, 43.861588], [-79.314641, 43.860383], [-79.325598, 43.857823], [-79.331026, 43.85654], [-79.334928, 43.855718], [-79.339009, 43.854388], [-79.345806, 43.852697], [-79.351627, 43.851326], [-79.357736, 43.850185], [-79.360991, 43.849433], [-79.364169, 43.848691], [-79.377773, 43.845621], [-79.382009, 43.844696], [-79.386052, 43.84379], [-79.39149, 43.842433], [-79.394947, 43.841639], [-79.398037, 43.840961], [-79.405394, 43.84019], [-79.409187, 43.844984], [-79.411308, 43.844197], [-79.414573, 43.843036], [-79.416281, 43.842809], [-79.41975, 43.842683], [-79.422957, 43.841393], [-79.421021, 43.839908], [-79.425239, 43.839817]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_f8dbaaebef7cfa9d856720d9fd5c723d.bindTooltip(
                `<div>
                     1 HIGHWAY 7
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_f8dbaaebef7cfa9d856720d9fd5c723d.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_0740aa79ee0ff2f9e363901832397a0b_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#496E6E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_0740aa79ee0ff2f9e363901832397a0b_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_0740aa79ee0ff2f9e363901832397a0b = L.geoJson(null, {
                onEachFeature: geo_json_0740aa79ee0ff2f9e363901832397a0b_onEachFeature,
            
                style: geo_json_0740aa79ee0ff2f9e363901832397a0b_styler,
            ...{
}
        });

        function geo_json_0740aa79ee0ff2f9e363901832397a0b_add (data) {
            geo_json_0740aa79ee0ff2f9e363901832397a0b
                .addData(data);
        }
            geo_json_0740aa79ee0ff2f9e363901832397a0b_add({"features": [{"geometry": {"coordinates": [[-79.357736, 43.850185], [-79.360991, 43.849433], [-79.364169, 43.848691], [-79.377773, 43.845621], [-79.382009, 43.844696], [-79.386052, 43.84379], [-79.39149, 43.842433], [-79.394947, 43.841639], [-79.398037, 43.840961], [-79.405394, 43.84019], [-79.409187, 43.844984], [-79.411308, 43.844197], [-79.414573, 43.843036], [-79.416281, 43.842809], [-79.41975, 43.842683], [-79.422957, 43.841393], [-79.421021, 43.839908], [-79.425239, 43.839817]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_0740aa79ee0ff2f9e363901832397a0b.bindTooltip(
                `<div>
                     1 HIGHWAY 7
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_0740aa79ee0ff2f9e363901832397a0b.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_769c7ba6abc7316fe05c0b2b95336ad3_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#C4A006", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_769c7ba6abc7316fe05c0b2b95336ad3_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_769c7ba6abc7316fe05c0b2b95336ad3 = L.geoJson(null, {
                onEachFeature: geo_json_769c7ba6abc7316fe05c0b2b95336ad3_onEachFeature,
            
                style: geo_json_769c7ba6abc7316fe05c0b2b95336ad3_styler,
            ...{
}
        });

        function geo_json_769c7ba6abc7316fe05c0b2b95336ad3_add (data) {
            geo_json_769c7ba6abc7316fe05c0b2b95336ad3
                .addData(data);
        }
            geo_json_769c7ba6abc7316fe05c0b2b95336ad3_add({"features": [{"geometry": {"coordinates": [[-79.415666, 43.782573], [-79.416698, 43.78496], [-79.417335, 43.787532], [-79.417977, 43.790138], [-79.418316, 43.79149], [-79.418994, 43.794272], [-79.42011, 43.798695], [-79.420878, 43.801684], [-79.417982, 43.802629], [-79.415599, 43.804078], [-79.413948, 43.804592], [-79.411505, 43.805334], [-79.409164, 43.806107], [-79.409195, 43.807414], [-79.41017, 43.809711], [-79.410569, 43.811474], [-79.410333, 43.813968], [-79.411054, 43.815862], [-79.403582, 43.818127], [-79.399974, 43.818698], [-79.398076, 43.819085], [-79.392546, 43.820053], [-79.388203, 43.820321], [-79.384522, 43.819883], [-79.381479, 43.820266], [-79.379687, 43.820479], [-79.377729, 43.820718], [-79.372834, 43.82164], [-79.370339, 43.822161], [-79.367144, 43.82293], [-79.359188, 43.824725], [-79.356782, 43.825163], [-79.353485, 43.825027], [-79.351947, 43.825141], [-79.348855, 43.825845], [-79.345585, 43.82701], [-79.343335, 43.827535], [-79.341632, 43.827824], [-79.34029, 43.827477], [-79.338844, 43.826468], [-79.33477, 43.82551], [-79.330732, 43.826439], [-79.328298, 43.826968], [-79.327003, 43.827289], [-79.322688, 43.830728], [-79.319121, 43.832678], [-79.316252, 43.833666], [-79.313966, 43.83418], [-79.308624, 43.83483], [-79.304755, 43.834472], [-79.301387, 43.833893], [-79.299357, 43.834085], [-79.296534, 43.834433], [-79.293475, 43.835671], [-79.289995, 43.83652], [-79.288172, 43.836917], [-79.285556, 43.837716], [-79.283669, 43.839053], [-79.280926, 43.840837], [-79.278361, 43.841367], [-79.274086, 43.84233], [-79.268546, 43.841638], [-79.265245, 43.841226], [-79.259973, 43.842274], [-79.256579, 43.843112], [-79.253439, 43.847631], [-79.254259, 43.851073], [-79.254791, 43.853275], [-79.254995, 43.85625], [-79.251469, 43.856335], [-79.249599, 43.858584], [-79.247389, 43.858753], [-79.244804, 43.85819], [-79.243773, 43.856081], [-79.240725, 43.855013], [-79.237612, 43.855779], [-79.237012, 43.858498], [-79.233443, 43.860308], [-79.234956, 43.861714], [-79.235964, 43.863304], [-79.234752, 43.865388], [-79.2328, 43.86463], [-79.23145, 43.863808], [-79.229191, 43.864961], [-79.228804, 43.865879], [-79.227586, 43.86825], [-79.224816, 43.869773], [-79.221362, 43.870486], [-79.215883, 43.869552], [-79.212178, 43.868989], [-79.219479, 43.881477], [-79.231813, 43.880902]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_769c7ba6abc7316fe05c0b2b95336ad3.bindTooltip(
                `<div>
                     2 MILLIKEN
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_769c7ba6abc7316fe05c0b2b95336ad3.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_8199fffd895b37a4428f970081eb92f4_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#C4A006", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_8199fffd895b37a4428f970081eb92f4_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_8199fffd895b37a4428f970081eb92f4 = L.geoJson(null, {
                onEachFeature: geo_json_8199fffd895b37a4428f970081eb92f4_onEachFeature,
            
                style: geo_json_8199fffd895b37a4428f970081eb92f4_styler,
            ...{
}
        });

        function geo_json_8199fffd895b37a4428f970081eb92f4_add (data) {
            geo_json_8199fffd895b37a4428f970081eb92f4
                .addData(data);
        }
            geo_json_8199fffd895b37a4428f970081eb92f4_add({"features": [{"geometry": {"coordinates": [[-79.231813, 43.880902], [-79.229019, 43.878971], [-79.219995, 43.881139], [-79.214597, 43.88235], [-79.212785, 43.869092], [-79.215888, 43.869834], [-79.220643, 43.870852], [-79.224298, 43.870037], [-79.228283, 43.867323], [-79.229206, 43.865536], [-79.232257, 43.863842], [-79.232877, 43.864886], [-79.234962, 43.865132], [-79.23604, 43.863676], [-79.235213, 43.861862], [-79.233822, 43.860387], [-79.23722, 43.857921], [-79.238215, 43.855653], [-79.240491, 43.855191], [-79.243854, 43.856569], [-79.244391, 43.857888], [-79.246777, 43.858916], [-79.249965, 43.858667], [-79.250189, 43.856946], [-79.25245, 43.85628], [-79.255242, 43.853693], [-79.254722, 43.851515], [-79.253878, 43.848047], [-79.253051, 43.844648], [-79.252176, 43.840846], [-79.253535, 43.840198], [-79.255378, 43.839764], [-79.257978, 43.839157], [-79.261564, 43.837352], [-79.264296, 43.836716], [-79.267291, 43.836413], [-79.266267, 43.837608], [-79.264689, 43.840549], [-79.265837, 43.841404], [-79.268183, 43.841711], [-79.27347, 43.842438], [-79.277679, 43.841691], [-79.280656, 43.84104], [-79.28352, 43.839334], [-79.285608, 43.837828], [-79.287737, 43.837138], [-79.289443, 43.836778], [-79.293133, 43.835902], [-79.296668, 43.834531], [-79.299021, 43.83424], [-79.302262, 43.833971], [-79.304058, 43.834436], [-79.308134, 43.835003], [-79.313561, 43.834374], [-79.316215, 43.833803], [-79.318485, 43.832946], [-79.322885, 43.830688], [-79.326288, 43.827609], [-79.327941, 43.827222], [-79.331583, 43.826384], [-79.334518, 43.825719], [-79.337274, 43.8251], [-79.338745, 43.826547], [-79.339736, 43.827468], [-79.343877, 43.827534], [-79.348884, 43.825984], [-79.351349, 43.825462], [-79.352366, 43.825231], [-79.356467, 43.825356], [-79.358667, 43.82494], [-79.36669, 43.82315], [-79.369824, 43.822506], [-79.372992, 43.821738], [-79.377696, 43.820836], [-79.379847, 43.820588], [-79.382036, 43.820329], [-79.384, 43.820105], [-79.387736, 43.820434], [-79.391877, 43.820376], [-79.397519, 43.819405], [-79.40051, 43.818836], [-79.403069, 43.818334], [-79.411115, 43.815593], [-79.410582, 43.814212], [-79.410699, 43.811487], [-79.410554, 43.810305], [-79.409585, 43.807995], [-79.409183, 43.806489], [-79.412666, 43.805103], [-79.414177, 43.804645], [-79.416282, 43.804004], [-79.418317, 43.802535], [-79.419729, 43.802093], [-79.420274, 43.798244], [-79.420037, 43.797434], [-79.419718, 43.796088], [-79.419191, 43.793992], [-79.418625, 43.791289], [-79.418069, 43.789452], [-79.417496, 43.7872], [-79.415666, 43.782573]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_8199fffd895b37a4428f970081eb92f4.bindTooltip(
                `<div>
                     2 MILLIKEN
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_8199fffd895b37a4428f970081eb92f4.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_83f48e8e1ce4088b5891780b255a4bff_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#C4A006", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_83f48e8e1ce4088b5891780b255a4bff_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_83f48e8e1ce4088b5891780b255a4bff = L.geoJson(null, {
                onEachFeature: geo_json_83f48e8e1ce4088b5891780b255a4bff_onEachFeature,
            
                style: geo_json_83f48e8e1ce4088b5891780b255a4bff_styler,
            ...{
}
        });

        function geo_json_83f48e8e1ce4088b5891780b255a4bff_add (data) {
            geo_json_83f48e8e1ce4088b5891780b255a4bff
                .addData(data);
        }
            geo_json_83f48e8e1ce4088b5891780b255a4bff_add({"features": [{"geometry": {"coordinates": [[-79.415666, 43.782573], [-79.416698, 43.78496], [-79.417335, 43.787532], [-79.417977, 43.790138], [-79.418316, 43.79149], [-79.418994, 43.794272], [-79.42011, 43.798695], [-79.420878, 43.801684], [-79.417982, 43.802629], [-79.415599, 43.804078], [-79.413948, 43.804592], [-79.411505, 43.805334], [-79.409164, 43.806107], [-79.409195, 43.807414], [-79.41017, 43.809711], [-79.410569, 43.811474], [-79.410333, 43.813968], [-79.411054, 43.815862], [-79.403582, 43.818127], [-79.399974, 43.818698], [-79.398076, 43.819085], [-79.392546, 43.820053], [-79.388203, 43.820321], [-79.384522, 43.819883], [-79.381479, 43.820266], [-79.379687, 43.820479], [-79.377729, 43.820718], [-79.372834, 43.82164], [-79.370339, 43.822161], [-79.367144, 43.82293], [-79.359188, 43.824725], [-79.356782, 43.825163], [-79.353485, 43.825027], [-79.351947, 43.825141], [-79.348855, 43.825845], [-79.345585, 43.82701], [-79.343335, 43.827535], [-79.341632, 43.827824], [-79.34029, 43.827477], [-79.338844, 43.826468], [-79.33477, 43.82551], [-79.330732, 43.826439], [-79.328298, 43.826968], [-79.327003, 43.827289], [-79.322688, 43.830728], [-79.319121, 43.832678], [-79.316252, 43.833666], [-79.313966, 43.83418], [-79.308624, 43.83483], [-79.304755, 43.834472], [-79.301387, 43.833893], [-79.299357, 43.834085], [-79.296534, 43.834433], [-79.293475, 43.835671], [-79.289995, 43.83652], [-79.288172, 43.836917], [-79.285556, 43.837716], [-79.283669, 43.839053], [-79.280926, 43.840837], [-79.278361, 43.841367], [-79.274086, 43.84233], [-79.268546, 43.841638], [-79.265245, 43.841226], [-79.259973, 43.842274], [-79.256579, 43.843112], [-79.253155, 43.844275]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_83f48e8e1ce4088b5891780b255a4bff.bindTooltip(
                `<div>
                     2 MILLIKEN
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_83f48e8e1ce4088b5891780b255a4bff.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_687967fa1e33fa3a2f3cc9c4b934f578_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#C4A006", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_687967fa1e33fa3a2f3cc9c4b934f578_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_687967fa1e33fa3a2f3cc9c4b934f578 = L.geoJson(null, {
                onEachFeature: geo_json_687967fa1e33fa3a2f3cc9c4b934f578_onEachFeature,
            
                style: geo_json_687967fa1e33fa3a2f3cc9c4b934f578_styler,
            ...{
}
        });

        function geo_json_687967fa1e33fa3a2f3cc9c4b934f578_add (data) {
            geo_json_687967fa1e33fa3a2f3cc9c4b934f578
                .addData(data);
        }
            geo_json_687967fa1e33fa3a2f3cc9c4b934f578_add({"features": [{"geometry": {"coordinates": [[-79.415666, 43.782573], [-79.416698, 43.78496], [-79.417335, 43.787532], [-79.417977, 43.790138], [-79.418316, 43.79149], [-79.418994, 43.794272], [-79.42011, 43.798695], [-79.420878, 43.801684], [-79.417982, 43.802629], [-79.415599, 43.804078], [-79.413948, 43.804592], [-79.411505, 43.805334], [-79.409164, 43.806107], [-79.409195, 43.807414], [-79.41017, 43.809711], [-79.410569, 43.811474], [-79.410333, 43.813968], [-79.411054, 43.815862], [-79.403582, 43.818127], [-79.399974, 43.818698], [-79.398076, 43.819085], [-79.392546, 43.820053], [-79.388203, 43.820321], [-79.384522, 43.819883], [-79.381479, 43.820266], [-79.379687, 43.820479], [-79.377729, 43.820718], [-79.372834, 43.82164], [-79.370339, 43.822161], [-79.367144, 43.82293], [-79.359188, 43.824725], [-79.356782, 43.825163], [-79.353485, 43.825027], [-79.351947, 43.825141], [-79.348855, 43.825845], [-79.345585, 43.82701], [-79.343335, 43.827535], [-79.341632, 43.827824], [-79.34029, 43.827477], [-79.338844, 43.826468], [-79.33477, 43.82551], [-79.330732, 43.826439], [-79.328298, 43.826968], [-79.327003, 43.827289], [-79.322688, 43.830728], [-79.319121, 43.832678], [-79.316252, 43.833666], [-79.313966, 43.83418], [-79.308624, 43.83483], [-79.304755, 43.834472], [-79.301387, 43.833893], [-79.299357, 43.834085], [-79.296534, 43.834433], [-79.293475, 43.835671], [-79.289995, 43.83652], [-79.288172, 43.836917], [-79.285556, 43.837716], [-79.283669, 43.839053], [-79.280926, 43.840837], [-79.278361, 43.841367], [-79.274086, 43.84233], [-79.268546, 43.841638], [-79.265064, 43.842008], [-79.265794, 43.84473], [-79.266538, 43.847832], [-79.261876, 43.849095], [-79.259978, 43.846026], [-79.25779, 43.843548], [-79.256579, 43.843112], [-79.253155, 43.844275]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_687967fa1e33fa3a2f3cc9c4b934f578.bindTooltip(
                `<div>
                     2 MILLIKEN
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_687967fa1e33fa3a2f3cc9c4b934f578.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_e914b470363a8ae62a16ab9b57f75e4c_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#C4A006", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_e914b470363a8ae62a16ab9b57f75e4c_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_e914b470363a8ae62a16ab9b57f75e4c = L.geoJson(null, {
                onEachFeature: geo_json_e914b470363a8ae62a16ab9b57f75e4c_onEachFeature,
            
                style: geo_json_e914b470363a8ae62a16ab9b57f75e4c_styler,
            ...{
}
        });

        function geo_json_e914b470363a8ae62a16ab9b57f75e4c_add (data) {
            geo_json_e914b470363a8ae62a16ab9b57f75e4c
                .addData(data);
        }
            geo_json_e914b470363a8ae62a16ab9b57f75e4c_add({"features": [{"geometry": {"coordinates": [[-79.351947, 43.825141], [-79.348855, 43.825845], [-79.345585, 43.82701], [-79.343335, 43.827535], [-79.341632, 43.827824], [-79.34029, 43.827477], [-79.338844, 43.826468], [-79.33477, 43.82551], [-79.330732, 43.826439], [-79.328298, 43.826968], [-79.327003, 43.827289], [-79.322688, 43.830728], [-79.319121, 43.832678], [-79.316252, 43.833666], [-79.313966, 43.83418], [-79.308624, 43.83483], [-79.304755, 43.834472], [-79.301387, 43.833893], [-79.299357, 43.834085], [-79.296534, 43.834433], [-79.293475, 43.835671], [-79.289995, 43.83652], [-79.288172, 43.836917], [-79.285556, 43.837716], [-79.283669, 43.839053], [-79.280926, 43.840837], [-79.278361, 43.841367], [-79.274086, 43.84233], [-79.268546, 43.841638], [-79.265245, 43.841226], [-79.259973, 43.842274], [-79.256579, 43.843112], [-79.253155, 43.844275]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_e914b470363a8ae62a16ab9b57f75e4c.bindTooltip(
                `<div>
                     2 MILLIKEN
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_e914b470363a8ae62a16ab9b57f75e4c.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_d3639bd46ff68afb4a524c0976e72f1e_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#C4A006", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_d3639bd46ff68afb4a524c0976e72f1e_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_d3639bd46ff68afb4a524c0976e72f1e = L.geoJson(null, {
                onEachFeature: geo_json_d3639bd46ff68afb4a524c0976e72f1e_onEachFeature,
            
                style: geo_json_d3639bd46ff68afb4a524c0976e72f1e_styler,
            ...{
}
        });

        function geo_json_d3639bd46ff68afb4a524c0976e72f1e_add (data) {
            geo_json_d3639bd46ff68afb4a524c0976e72f1e
                .addData(data);
        }
            geo_json_d3639bd46ff68afb4a524c0976e72f1e_add({"features": [{"geometry": {"coordinates": [[-79.253155, 43.844275], [-79.251161, 43.845047], [-79.249524, 43.845875], [-79.247047, 43.847115], [-79.245634, 43.844309], [-79.247826, 43.842224], [-79.246538, 43.840048], [-79.245475, 43.838179], [-79.248299, 43.837375], [-79.250771, 43.836844], [-79.25111, 43.838002], [-79.253535, 43.840198], [-79.255378, 43.839764], [-79.257978, 43.839157], [-79.261564, 43.837352], [-79.264296, 43.836716], [-79.267291, 43.836413], [-79.266267, 43.837608], [-79.264689, 43.840549], [-79.265837, 43.841404], [-79.268183, 43.841711], [-79.27347, 43.842438], [-79.277679, 43.841691], [-79.280656, 43.84104], [-79.28352, 43.839334], [-79.285608, 43.837828], [-79.287737, 43.837138], [-79.289443, 43.836778], [-79.293133, 43.835902], [-79.296668, 43.834531], [-79.299021, 43.83424], [-79.302262, 43.833971], [-79.304058, 43.834436], [-79.308134, 43.835003], [-79.313561, 43.834374], [-79.316215, 43.833803], [-79.318485, 43.832946], [-79.322885, 43.830688], [-79.326288, 43.827609], [-79.327941, 43.827222], [-79.331583, 43.826384], [-79.334518, 43.825719], [-79.337274, 43.8251], [-79.338745, 43.826547], [-79.339736, 43.827468], [-79.343877, 43.827534], [-79.348884, 43.825984], [-79.351349, 43.825462], [-79.352366, 43.825231], [-79.356467, 43.825356], [-79.358667, 43.82494], [-79.36669, 43.82315], [-79.369824, 43.822506], [-79.372992, 43.821738], [-79.377696, 43.820836], [-79.379847, 43.820588], [-79.382036, 43.820329], [-79.384, 43.820105], [-79.387736, 43.820434], [-79.391877, 43.820376], [-79.397519, 43.819405], [-79.40051, 43.818836], [-79.403069, 43.818334], [-79.411115, 43.815593], [-79.410582, 43.814212], [-79.410699, 43.811487], [-79.410554, 43.810305], [-79.409585, 43.807995], [-79.409183, 43.806489], [-79.412666, 43.805103], [-79.414177, 43.804645], [-79.416282, 43.804004], [-79.418317, 43.802535], [-79.419729, 43.802093], [-79.420274, 43.798244], [-79.420037, 43.797434], [-79.419718, 43.796088], [-79.419191, 43.793992], [-79.418625, 43.791289], [-79.418069, 43.789452], [-79.417496, 43.7872], [-79.415666, 43.782573]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_d3639bd46ff68afb4a524c0976e72f1e.bindTooltip(
                `<div>
                     2 MILLIKEN
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_d3639bd46ff68afb4a524c0976e72f1e.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_752091f82533ed7a600d7f53f0df2fbc_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#C4A006", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_752091f82533ed7a600d7f53f0df2fbc_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_752091f82533ed7a600d7f53f0df2fbc = L.geoJson(null, {
                onEachFeature: geo_json_752091f82533ed7a600d7f53f0df2fbc_onEachFeature,
            
                style: geo_json_752091f82533ed7a600d7f53f0df2fbc_styler,
            ...{
}
        });

        function geo_json_752091f82533ed7a600d7f53f0df2fbc_add (data) {
            geo_json_752091f82533ed7a600d7f53f0df2fbc
                .addData(data);
        }
            geo_json_752091f82533ed7a600d7f53f0df2fbc_add({"features": [{"geometry": {"coordinates": [[-79.253155, 43.844275], [-79.251161, 43.845047], [-79.249524, 43.845875], [-79.247047, 43.847115], [-79.245634, 43.844309], [-79.247826, 43.842224], [-79.246538, 43.840048], [-79.245475, 43.838179], [-79.248299, 43.837375], [-79.250771, 43.836844], [-79.25111, 43.838002], [-79.253535, 43.840198], [-79.255378, 43.839764], [-79.257978, 43.839157], [-79.261564, 43.837352], [-79.264296, 43.836716], [-79.267291, 43.836413], [-79.266267, 43.837608], [-79.264689, 43.840549], [-79.265064, 43.842008], [-79.265794, 43.84473], [-79.266538, 43.847832], [-79.261876, 43.849095], [-79.259978, 43.846026], [-79.25779, 43.843548], [-79.259527, 43.842574], [-79.264677, 43.841419], [-79.265837, 43.841404], [-79.268183, 43.841711], [-79.27347, 43.842438], [-79.277679, 43.841691], [-79.280656, 43.84104], [-79.28352, 43.839334], [-79.285608, 43.837828], [-79.287737, 43.837138], [-79.289443, 43.836778], [-79.293133, 43.835902], [-79.296668, 43.834531], [-79.299021, 43.83424], [-79.302262, 43.833971], [-79.304058, 43.834436], [-79.308134, 43.835003], [-79.313561, 43.834374], [-79.316215, 43.833803], [-79.318485, 43.832946], [-79.322885, 43.830688], [-79.326288, 43.827609], [-79.327941, 43.827222], [-79.331583, 43.826384], [-79.334518, 43.825719], [-79.337274, 43.8251], [-79.338745, 43.826547], [-79.339736, 43.827468], [-79.343877, 43.827534], [-79.348884, 43.825984], [-79.351349, 43.825462], [-79.352366, 43.825231], [-79.356467, 43.825356], [-79.358667, 43.82494], [-79.36669, 43.82315], [-79.369824, 43.822506], [-79.372992, 43.821738], [-79.377696, 43.820836], [-79.379847, 43.820588], [-79.382036, 43.820329], [-79.384, 43.820105], [-79.387736, 43.820434], [-79.391877, 43.820376], [-79.397519, 43.819405], [-79.40051, 43.818836], [-79.403069, 43.818334], [-79.411115, 43.815593], [-79.410582, 43.814212], [-79.410699, 43.811487], [-79.410554, 43.810305], [-79.409585, 43.807995], [-79.409183, 43.806489], [-79.412666, 43.805103], [-79.414177, 43.804645], [-79.416282, 43.804004], [-79.418317, 43.802535], [-79.419729, 43.802093], [-79.420274, 43.798244], [-79.420037, 43.797434], [-79.419718, 43.796088], [-79.419191, 43.793992], [-79.418625, 43.791289], [-79.418069, 43.789452], [-79.417496, 43.7872], [-79.415666, 43.782573]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_752091f82533ed7a600d7f53f0df2fbc.bindTooltip(
                `<div>
                     2 MILLIKEN
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_752091f82533ed7a600d7f53f0df2fbc.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_83ab15e959c5464d6adfc655ce7e46cd_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#C4A006", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_83ab15e959c5464d6adfc655ce7e46cd_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_83ab15e959c5464d6adfc655ce7e46cd = L.geoJson(null, {
                onEachFeature: geo_json_83ab15e959c5464d6adfc655ce7e46cd_onEachFeature,
            
                style: geo_json_83ab15e959c5464d6adfc655ce7e46cd_styler,
            ...{
}
        });

        function geo_json_83ab15e959c5464d6adfc655ce7e46cd_add (data) {
            geo_json_83ab15e959c5464d6adfc655ce7e46cd
                .addData(data);
        }
            geo_json_83ab15e959c5464d6adfc655ce7e46cd_add({"features": [{"geometry": {"coordinates": [[-79.352366, 43.825231], [-79.356467, 43.825356], [-79.358667, 43.82494], [-79.36669, 43.82315], [-79.369824, 43.822506], [-79.372992, 43.821738], [-79.377696, 43.820836], [-79.379847, 43.820588], [-79.382036, 43.820329], [-79.384, 43.820105], [-79.387736, 43.820434], [-79.391877, 43.820376], [-79.397519, 43.819405], [-79.40051, 43.818836], [-79.403069, 43.818334], [-79.411115, 43.815593], [-79.410582, 43.814212], [-79.410699, 43.811487], [-79.410554, 43.810305], [-79.409585, 43.807995], [-79.409183, 43.806489], [-79.412666, 43.805103], [-79.414177, 43.804645], [-79.416282, 43.804004], [-79.418317, 43.802535], [-79.419729, 43.802093], [-79.420274, 43.798244], [-79.420037, 43.797434], [-79.419718, 43.796088], [-79.419191, 43.793992], [-79.418625, 43.791289], [-79.418069, 43.789452], [-79.417496, 43.7872], [-79.415666, 43.782573]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_83ab15e959c5464d6adfc655ce7e46cd.bindTooltip(
                `<div>
                     2 MILLIKEN
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_83ab15e959c5464d6adfc655ce7e46cd.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_42490caa41b065ac12e86f7fd75309c4_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#C4A006", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_42490caa41b065ac12e86f7fd75309c4_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_42490caa41b065ac12e86f7fd75309c4 = L.geoJson(null, {
                onEachFeature: geo_json_42490caa41b065ac12e86f7fd75309c4_onEachFeature,
            
                style: geo_json_42490caa41b065ac12e86f7fd75309c4_styler,
            ...{
}
        });

        function geo_json_42490caa41b065ac12e86f7fd75309c4_add (data) {
            geo_json_42490caa41b065ac12e86f7fd75309c4
                .addData(data);
        }
            geo_json_42490caa41b065ac12e86f7fd75309c4_add({"features": [{"geometry": {"coordinates": [[-79.253155, 43.844275], [-79.251161, 43.845047], [-79.249524, 43.845875], [-79.247047, 43.847115], [-79.245634, 43.844309], [-79.247826, 43.842224], [-79.246538, 43.840048], [-79.245475, 43.838179], [-79.248299, 43.837375], [-79.250771, 43.836844], [-79.25111, 43.838002], [-79.253535, 43.840198], [-79.255378, 43.839764], [-79.257978, 43.839157], [-79.261564, 43.837352], [-79.264296, 43.836716], [-79.267291, 43.836413], [-79.266267, 43.837608], [-79.264689, 43.840549]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_42490caa41b065ac12e86f7fd75309c4.bindTooltip(
                `<div>
                     2 MILLIKEN
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_42490caa41b065ac12e86f7fd75309c4.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_13a4876d5018a3af0625c00fb837c5b1_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A54686", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_13a4876d5018a3af0625c00fb837c5b1_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_13a4876d5018a3af0625c00fb837c5b1 = L.geoJson(null, {
                onEachFeature: geo_json_13a4876d5018a3af0625c00fb837c5b1_onEachFeature,
            
                style: geo_json_13a4876d5018a3af0625c00fb837c5b1_styler,
            ...{
}
        });

        function geo_json_13a4876d5018a3af0625c00fb837c5b1_add (data) {
            geo_json_13a4876d5018a3af0625c00fb837c5b1
                .addData(data);
        }
            geo_json_13a4876d5018a3af0625c00fb837c5b1_add({"features": [{"geometry": {"coordinates": [[-79.358781, 43.812704], [-79.36857, 43.817466], [-79.367995, 43.815857], [-79.36581, 43.813176], [-79.362221, 43.813973]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_13a4876d5018a3af0625c00fb837c5b1.bindTooltip(
                `<div>
                     3 THORNHILL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_13a4876d5018a3af0625c00fb837c5b1.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_56ba6c3ebd7da07a925a67927d91886a_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A54686", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_56ba6c3ebd7da07a925a67927d91886a_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_56ba6c3ebd7da07a925a67927d91886a = L.geoJson(null, {
                onEachFeature: geo_json_56ba6c3ebd7da07a925a67927d91886a_onEachFeature,
            
                style: geo_json_56ba6c3ebd7da07a925a67927d91886a_styler,
            ...{
}
        });

        function geo_json_56ba6c3ebd7da07a925a67927d91886a_add (data) {
            geo_json_56ba6c3ebd7da07a925a67927d91886a
                .addData(data);
        }
            geo_json_56ba6c3ebd7da07a925a67927d91886a_add({"features": [{"geometry": {"coordinates": [[-79.425788, 43.822633], [-79.423779, 43.822985], [-79.420963, 43.823082], [-79.417155, 43.823978], [-79.412835, 43.82438], [-79.409324, 43.824208], [-79.406765, 43.824601], [-79.404462, 43.824736], [-79.402301, 43.822173], [-79.400847, 43.819746], [-79.40051, 43.818836], [-79.401617, 43.821607], [-79.403256, 43.827992], [-79.40266, 43.828204], [-79.399457, 43.828655], [-79.398411, 43.829728], [-79.397656, 43.831061], [-79.394321, 43.831271], [-79.392946, 43.829956], [-79.39162, 43.828665], [-79.389816, 43.826813], [-79.388532, 43.823945], [-79.384864, 43.824733], [-79.380194, 43.82576], [-79.377949, 43.827512], [-79.37823, 43.829448], [-79.376936, 43.830524], [-79.372032, 43.829082], [-79.371314, 43.826734], [-79.369937, 43.82163], [-79.367274, 43.819227], [-79.362201, 43.814192], [-79.358781, 43.812704]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_56ba6c3ebd7da07a925a67927d91886a.bindTooltip(
                `<div>
                     3 THORNHILL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_56ba6c3ebd7da07a925a67927d91886a.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_32e27c5d571f8c5889819c42131870c1_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A54686", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_32e27c5d571f8c5889819c42131870c1_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_32e27c5d571f8c5889819c42131870c1 = L.geoJson(null, {
                onEachFeature: geo_json_32e27c5d571f8c5889819c42131870c1_onEachFeature,
            
                style: geo_json_32e27c5d571f8c5889819c42131870c1_styler,
            ...{
}
        });

        function geo_json_32e27c5d571f8c5889819c42131870c1_add (data) {
            geo_json_32e27c5d571f8c5889819c42131870c1
                .addData(data);
        }
            geo_json_32e27c5d571f8c5889819c42131870c1_add({"features": [{"geometry": {"coordinates": [[-79.512107, 43.77864], [-79.507342, 43.778448], [-79.503784, 43.779254], [-79.493765, 43.781611], [-79.490237, 43.782446], [-79.487481, 43.783097], [-79.482804, 43.784194], [-79.48028, 43.784779], [-79.477823, 43.78538], [-79.475086, 43.786009], [-79.470466, 43.787069], [-79.463365, 43.78853], [-79.458112, 43.791718], [-79.459076, 43.795762], [-79.459028, 43.798817], [-79.457744, 43.801747], [-79.456021, 43.805895], [-79.457127, 43.809215], [-79.454, 43.80934], [-79.457067, 43.809698], [-79.457386, 43.811477], [-79.456574, 43.813972], [-79.455061, 43.816072], [-79.452016, 43.817083], [-79.45012, 43.817482], [-79.446533, 43.818126], [-79.44471, 43.817234], [-79.443736, 43.815744], [-79.443649, 43.813662], [-79.442814, 43.812325], [-79.438628, 43.813223], [-79.436276, 43.813747], [-79.432606, 43.814526], [-79.427575, 43.815604], [-79.425221, 43.816138], [-79.425788, 43.822633], [-79.423779, 43.822985], [-79.420963, 43.823082], [-79.417155, 43.823978], [-79.412835, 43.82438], [-79.409324, 43.824208], [-79.406765, 43.824601], [-79.404462, 43.824736], [-79.402301, 43.822173], [-79.400847, 43.819746], [-79.40051, 43.818836], [-79.401617, 43.821607], [-79.403256, 43.827992], [-79.40266, 43.828204], [-79.399457, 43.828655], [-79.398411, 43.829728], [-79.397656, 43.831061], [-79.394321, 43.831271], [-79.392946, 43.829956], [-79.39162, 43.828665], [-79.389816, 43.826813], [-79.388532, 43.823945], [-79.384864, 43.824733], [-79.380194, 43.82576], [-79.377949, 43.827512], [-79.37823, 43.829448], [-79.376936, 43.830524], [-79.372032, 43.829082], [-79.371314, 43.826734], [-79.369937, 43.82163], [-79.367274, 43.819227], [-79.362201, 43.814192], [-79.358781, 43.812704]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_32e27c5d571f8c5889819c42131870c1.bindTooltip(
                `<div>
                     3 THORNHILL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_32e27c5d571f8c5889819c42131870c1.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_0f4edd0c138cd098c73dbcaefcf7b67a_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A54686", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_0f4edd0c138cd098c73dbcaefcf7b67a_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_0f4edd0c138cd098c73dbcaefcf7b67a = L.geoJson(null, {
                onEachFeature: geo_json_0f4edd0c138cd098c73dbcaefcf7b67a_onEachFeature,
            
                style: geo_json_0f4edd0c138cd098c73dbcaefcf7b67a_styler,
            ...{
}
        });

        function geo_json_0f4edd0c138cd098c73dbcaefcf7b67a_add (data) {
            geo_json_0f4edd0c138cd098c73dbcaefcf7b67a
                .addData(data);
        }
            geo_json_0f4edd0c138cd098c73dbcaefcf7b67a_add({"features": [{"geometry": {"coordinates": [[-79.358781, 43.812704], [-79.360853, 43.81163], [-79.361859, 43.813989], [-79.36857, 43.817466], [-79.367995, 43.815857], [-79.36581, 43.813176], [-79.362221, 43.813973], [-79.359907, 43.815483], [-79.360543, 43.817041], [-79.361261, 43.818737], [-79.362466, 43.821301], [-79.36554, 43.820788], [-79.366915, 43.819543], [-79.369799, 43.822068], [-79.370925, 43.826409], [-79.371997, 43.829491], [-79.377226, 43.830443], [-79.378479, 43.829421], [-79.379693, 43.825962], [-79.38452, 43.82491], [-79.389039, 43.823963], [-79.389807, 43.82708], [-79.391412, 43.828496], [-79.39269, 43.829901], [-79.394156, 43.831322], [-79.397527, 43.831267], [-79.398593, 43.830285], [-79.399409, 43.828782], [-79.402806, 43.828295], [-79.402064, 43.821857], [-79.400847, 43.819746], [-79.40051, 43.818836], [-79.401617, 43.821607], [-79.404234, 43.824882], [-79.406731, 43.824693], [-79.409147, 43.824284], [-79.412392, 43.824454], [-79.416819, 43.824205], [-79.421181, 43.823151], [-79.424686, 43.823107], [-79.424704, 43.816482], [-79.428161, 43.815589], [-79.432384, 43.81469], [-79.435924, 43.813938], [-79.438198, 43.813455], [-79.4428, 43.81248], [-79.443439, 43.813424], [-79.443515, 43.815277], [-79.444961, 43.817619], [-79.451178, 43.817412], [-79.453808, 43.816829], [-79.456625, 43.814422], [-79.457502, 43.811805], [-79.453914, 43.809497], [-79.455437, 43.806182], [-79.457845, 43.802277], [-79.459539, 43.798247], [-79.459378, 43.796188], [-79.458403, 43.79209], [-79.457864, 43.790128], [-79.462964, 43.788861], [-79.46978, 43.787478], [-79.474517, 43.786367], [-79.47807, 43.785541], [-79.480873, 43.784884], [-79.48294, 43.784391], [-79.48704, 43.783436], [-79.489825, 43.78278], [-79.494203, 43.781737], [-79.504245, 43.779419], [-79.510792, 43.777917], [-79.512107, 43.77864]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_0f4edd0c138cd098c73dbcaefcf7b67a.bindTooltip(
                `<div>
                     3 THORNHILL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_0f4edd0c138cd098c73dbcaefcf7b67a.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_f2393354fb9e3fb3dbdad46d5457d408_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A54686", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_f2393354fb9e3fb3dbdad46d5457d408_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_f2393354fb9e3fb3dbdad46d5457d408 = L.geoJson(null, {
                onEachFeature: geo_json_f2393354fb9e3fb3dbdad46d5457d408_onEachFeature,
            
                style: geo_json_f2393354fb9e3fb3dbdad46d5457d408_styler,
            ...{
}
        });

        function geo_json_f2393354fb9e3fb3dbdad46d5457d408_add (data) {
            geo_json_f2393354fb9e3fb3dbdad46d5457d408
                .addData(data);
        }
            geo_json_f2393354fb9e3fb3dbdad46d5457d408_add({"features": [{"geometry": {"coordinates": [[-79.358781, 43.812704], [-79.360853, 43.81163], [-79.361859, 43.813989], [-79.36857, 43.817466], [-79.367995, 43.815857], [-79.36581, 43.813176], [-79.362221, 43.813973], [-79.359907, 43.815483], [-79.360543, 43.817041], [-79.361261, 43.818737], [-79.362466, 43.821301], [-79.36554, 43.820788], [-79.366915, 43.819543], [-79.369799, 43.822068], [-79.370925, 43.826409], [-79.371997, 43.829491], [-79.377226, 43.830443], [-79.378479, 43.829421], [-79.379693, 43.825962], [-79.38452, 43.82491], [-79.389039, 43.823963], [-79.389807, 43.82708], [-79.391412, 43.828496], [-79.39269, 43.829901], [-79.394156, 43.831322], [-79.397527, 43.831267], [-79.398593, 43.830285], [-79.399409, 43.828782], [-79.402806, 43.828295], [-79.402064, 43.821857], [-79.400847, 43.819746], [-79.40051, 43.818836], [-79.401617, 43.821607], [-79.404234, 43.824882], [-79.406731, 43.824693], [-79.409147, 43.824284], [-79.412392, 43.824454], [-79.416819, 43.824205], [-79.421181, 43.823151], [-79.424686, 43.823107]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_f2393354fb9e3fb3dbdad46d5457d408.bindTooltip(
                `<div>
                     3 THORNHILL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_f2393354fb9e3fb3dbdad46d5457d408.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_73d838567dc77833f1f8ed016e0b813f_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A54686", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_73d838567dc77833f1f8ed016e0b813f_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_73d838567dc77833f1f8ed016e0b813f = L.geoJson(null, {
                onEachFeature: geo_json_73d838567dc77833f1f8ed016e0b813f_onEachFeature,
            
                style: geo_json_73d838567dc77833f1f8ed016e0b813f_styler,
            ...{
}
        });

        function geo_json_73d838567dc77833f1f8ed016e0b813f_add (data) {
            geo_json_73d838567dc77833f1f8ed016e0b813f
                .addData(data);
        }
            geo_json_73d838567dc77833f1f8ed016e0b813f_add({"features": [{"geometry": {"coordinates": [[-79.454, 43.80934], [-79.457067, 43.809698], [-79.457386, 43.811477], [-79.456574, 43.813972], [-79.455061, 43.816072], [-79.452016, 43.817083], [-79.45012, 43.817482], [-79.446533, 43.818126], [-79.44471, 43.817234], [-79.443736, 43.815744], [-79.443649, 43.813662], [-79.442814, 43.812325], [-79.438628, 43.813223], [-79.436276, 43.813747], [-79.432606, 43.814526], [-79.427575, 43.815604], [-79.425221, 43.816138], [-79.425788, 43.822633], [-79.423779, 43.822985], [-79.420963, 43.823082], [-79.417155, 43.823978], [-79.412835, 43.82438], [-79.409324, 43.824208], [-79.406765, 43.824601], [-79.404462, 43.824736], [-79.402301, 43.822173], [-79.400847, 43.819746], [-79.40051, 43.818836], [-79.401617, 43.821607], [-79.403256, 43.827992], [-79.40266, 43.828204], [-79.399457, 43.828655], [-79.398411, 43.829728], [-79.397656, 43.831061], [-79.394321, 43.831271], [-79.392946, 43.829956], [-79.39162, 43.828665], [-79.389816, 43.826813], [-79.388532, 43.823945], [-79.384864, 43.824733], [-79.380194, 43.82576], [-79.377949, 43.827512], [-79.37823, 43.829448], [-79.376936, 43.830524], [-79.372032, 43.829082], [-79.371314, 43.826734], [-79.369937, 43.82163], [-79.367274, 43.819227], [-79.362201, 43.814192], [-79.358781, 43.812704]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_73d838567dc77833f1f8ed016e0b813f.bindTooltip(
                `<div>
                     3 THORNHILL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_73d838567dc77833f1f8ed016e0b813f.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_9fc3c06e7427025247c6e729fa814646_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A54686", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_9fc3c06e7427025247c6e729fa814646_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_9fc3c06e7427025247c6e729fa814646 = L.geoJson(null, {
                onEachFeature: geo_json_9fc3c06e7427025247c6e729fa814646_onEachFeature,
            
                style: geo_json_9fc3c06e7427025247c6e729fa814646_styler,
            ...{
}
        });

        function geo_json_9fc3c06e7427025247c6e729fa814646_add (data) {
            geo_json_9fc3c06e7427025247c6e729fa814646
                .addData(data);
        }
            geo_json_9fc3c06e7427025247c6e729fa814646_add({"features": [{"geometry": {"coordinates": [[-79.453914, 43.809497], [-79.455437, 43.806182], [-79.457845, 43.802277], [-79.459539, 43.798247], [-79.459378, 43.796188], [-79.458403, 43.79209], [-79.457864, 43.790128], [-79.462964, 43.788861], [-79.46978, 43.787478], [-79.474517, 43.786367], [-79.47807, 43.785541], [-79.480873, 43.784884], [-79.48294, 43.784391], [-79.48704, 43.783436], [-79.489825, 43.78278], [-79.494203, 43.781737], [-79.504245, 43.779419], [-79.510792, 43.777917], [-79.512107, 43.77864]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_9fc3c06e7427025247c6e729fa814646.bindTooltip(
                `<div>
                     3 THORNHILL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_9fc3c06e7427025247c6e729fa814646.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_e98c1ac139db44b49469d0427b67cb81_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0058A9", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_e98c1ac139db44b49469d0427b67cb81_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_e98c1ac139db44b49469d0427b67cb81 = L.geoJson(null, {
                onEachFeature: geo_json_e98c1ac139db44b49469d0427b67cb81_onEachFeature,
            
                style: geo_json_e98c1ac139db44b49469d0427b67cb81_styler,
            ...{
}
        });

        function geo_json_e98c1ac139db44b49469d0427b67cb81_add (data) {
            geo_json_e98c1ac139db44b49469d0427b67cb81
                .addData(data);
        }
            geo_json_e98c1ac139db44b49469d0427b67cb81_add({"features": [{"geometry": {"coordinates": [[-79.581976, 43.840486], [-79.576877, 43.841472], [-79.571919, 43.842457], [-79.566987, 43.843502], [-79.560792, 43.844748], [-79.55736, 43.845084], [-79.554366, 43.845382], [-79.540164, 43.847623], [-79.536968, 43.84925], [-79.534676, 43.850013], [-79.532337, 43.85072], [-79.526266, 43.851972], [-79.520817, 43.853061], [-79.518076, 43.853615], [-79.512653, 43.854715], [-79.511638, 43.855002], [-79.508724, 43.856212], [-79.502883, 43.857535], [-79.499138, 43.858335], [-79.494105, 43.859507], [-79.487967, 43.861009], [-79.482866, 43.861967], [-79.468887, 43.864623], [-79.463954, 43.865603], [-79.457965, 43.866675], [-79.453622, 43.867643], [-79.449096, 43.868574], [-79.443744, 43.869707], [-79.440822, 43.870331], [-79.437609, 43.871055], [-79.434281, 43.87184], [-79.430302, 43.872728], [-79.428468, 43.873121], [-79.42471, 43.8739], [-79.421289, 43.874668], [-79.418196, 43.875363], [-79.415815, 43.875861], [-79.412503, 43.876103], [-79.406801, 43.876794], [-79.400789, 43.878096], [-79.39694, 43.878923], [-79.392005, 43.880199], [-79.386694, 43.881611], [-79.373531, 43.884489], [-79.370487, 43.885128], [-79.36778, 43.88568], [-79.366976, 43.884408], [-79.366257, 43.881318], [-79.365167, 43.876989], [-79.368041, 43.876536], [-79.371399, 43.876124], [-79.37251, 43.87885], [-79.374015, 43.880748], [-79.376179, 43.879721], [-79.374135, 43.875634], [-79.372265, 43.875854]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_e98c1ac139db44b49469d0427b67cb81.bindTooltip(
                `<div>
                     4 MAJOR MACKENZIE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_e98c1ac139db44b49469d0427b67cb81.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_d9fa7c27005630ae9e2390cc3cefd28d_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0058A9", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_d9fa7c27005630ae9e2390cc3cefd28d_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_d9fa7c27005630ae9e2390cc3cefd28d = L.geoJson(null, {
                onEachFeature: geo_json_d9fa7c27005630ae9e2390cc3cefd28d_onEachFeature,
            
                style: geo_json_d9fa7c27005630ae9e2390cc3cefd28d_styler,
            ...{
}
        });

        function geo_json_d9fa7c27005630ae9e2390cc3cefd28d_add (data) {
            geo_json_d9fa7c27005630ae9e2390cc3cefd28d
                .addData(data);
        }
            geo_json_d9fa7c27005630ae9e2390cc3cefd28d_add({"features": [{"geometry": {"coordinates": [[-79.511638, 43.855002], [-79.508724, 43.856212], [-79.502883, 43.857535], [-79.499138, 43.858335], [-79.494105, 43.859507], [-79.487967, 43.861009], [-79.482866, 43.861967], [-79.468887, 43.864623], [-79.463954, 43.865603], [-79.457965, 43.866675], [-79.453622, 43.867643], [-79.449096, 43.868574], [-79.443744, 43.869707], [-79.440822, 43.870331], [-79.437609, 43.871055], [-79.434281, 43.87184], [-79.430302, 43.872728], [-79.428468, 43.873121], [-79.42471, 43.8739], [-79.421289, 43.874668], [-79.418196, 43.875363], [-79.415815, 43.875861], [-79.412503, 43.876103], [-79.406801, 43.876794], [-79.400789, 43.878096], [-79.39694, 43.878923], [-79.392005, 43.880199], [-79.386694, 43.881611], [-79.373531, 43.884489], [-79.370487, 43.885128], [-79.36778, 43.88568], [-79.366976, 43.884408], [-79.366257, 43.881318], [-79.365167, 43.876989], [-79.368041, 43.876536], [-79.371399, 43.876124], [-79.37251, 43.87885], [-79.374015, 43.880748], [-79.376179, 43.879721], [-79.374135, 43.875634], [-79.372265, 43.875854]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_d9fa7c27005630ae9e2390cc3cefd28d.bindTooltip(
                `<div>
                     4 MAJOR MACKENZIE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_d9fa7c27005630ae9e2390cc3cefd28d.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_faedd13a8fd9726f6ca8c06030acd8c6_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0058A9", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_faedd13a8fd9726f6ca8c06030acd8c6_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_faedd13a8fd9726f6ca8c06030acd8c6 = L.geoJson(null, {
                onEachFeature: geo_json_faedd13a8fd9726f6ca8c06030acd8c6_onEachFeature,
            
                style: geo_json_faedd13a8fd9726f6ca8c06030acd8c6_styler,
            ...{
}
        });

        function geo_json_faedd13a8fd9726f6ca8c06030acd8c6_add (data) {
            geo_json_faedd13a8fd9726f6ca8c06030acd8c6
                .addData(data);
        }
            geo_json_faedd13a8fd9726f6ca8c06030acd8c6_add({"features": [{"geometry": {"coordinates": [[-79.372265, 43.875854], [-79.368658, 43.876342], [-79.365701, 43.876642], [-79.365843, 43.880997], [-79.36836, 43.885802], [-79.369982, 43.885476], [-79.372872, 43.884904], [-79.385776, 43.882037], [-79.391179, 43.880703], [-79.395855, 43.879422], [-79.400067, 43.8785], [-79.406142, 43.877191], [-79.411998, 43.876305], [-79.415047, 43.876239], [-79.416725, 43.875857], [-79.420892, 43.874917], [-79.425135, 43.874038], [-79.427908, 43.873424], [-79.430266, 43.872892], [-79.433853, 43.872082], [-79.436912, 43.871414], [-79.44391, 43.869902], [-79.448474, 43.868924], [-79.453965, 43.867734], [-79.457412, 43.867029], [-79.462371, 43.866089], [-79.468446, 43.864898], [-79.482129, 43.862312], [-79.48681, 43.861504], [-79.498376, 43.858756], [-79.502577, 43.857747], [-79.508495, 43.856407], [-79.511917, 43.855122], [-79.516385, 43.854123], [-79.520313, 43.853344], [-79.526866, 43.85207], [-79.531817, 43.851079], [-79.534377, 43.850369], [-79.536186, 43.849826], [-79.540904, 43.84761], [-79.553825, 43.845763], [-79.556489, 43.84532], [-79.560167, 43.845018], [-79.567416, 43.84362], [-79.571313, 43.842827], [-79.575918, 43.839615], [-79.576148, 43.837537], [-79.577432, 43.833918], [-79.579582, 43.833789], [-79.58338, 43.833043], [-79.586173, 43.839563], [-79.581976, 43.840486]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_faedd13a8fd9726f6ca8c06030acd8c6.bindTooltip(
                `<div>
                     4 MAJOR MACKENZIE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_faedd13a8fd9726f6ca8c06030acd8c6.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_7f58298141a18ac7768793d7aaafb45c_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0058A9", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_7f58298141a18ac7768793d7aaafb45c_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_7f58298141a18ac7768793d7aaafb45c = L.geoJson(null, {
                onEachFeature: geo_json_7f58298141a18ac7768793d7aaafb45c_onEachFeature,
            
                style: geo_json_7f58298141a18ac7768793d7aaafb45c_styler,
            ...{
}
        });

        function geo_json_7f58298141a18ac7768793d7aaafb45c_add (data) {
            geo_json_7f58298141a18ac7768793d7aaafb45c
                .addData(data);
        }
            geo_json_7f58298141a18ac7768793d7aaafb45c_add({"features": [{"geometry": {"coordinates": [[-79.448474, 43.868924], [-79.453965, 43.867734], [-79.457412, 43.867029], [-79.462371, 43.866089], [-79.468446, 43.864898], [-79.482129, 43.862312], [-79.48681, 43.861504], [-79.498376, 43.858756], [-79.502577, 43.857747], [-79.508495, 43.856407], [-79.511917, 43.855122], [-79.516385, 43.854123], [-79.520313, 43.853344], [-79.526866, 43.85207], [-79.531817, 43.851079], [-79.534377, 43.850369], [-79.536186, 43.849826], [-79.540904, 43.84761]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_7f58298141a18ac7768793d7aaafb45c.bindTooltip(
                `<div>
                     4 MAJOR MACKENZIE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_7f58298141a18ac7768793d7aaafb45c.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_729357318759c22fdacfcf1a3fb204a1_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0058A9", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_729357318759c22fdacfcf1a3fb204a1_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_729357318759c22fdacfcf1a3fb204a1 = L.geoJson(null, {
                onEachFeature: geo_json_729357318759c22fdacfcf1a3fb204a1_onEachFeature,
            
                style: geo_json_729357318759c22fdacfcf1a3fb204a1_styler,
            ...{
}
        });

        function geo_json_729357318759c22fdacfcf1a3fb204a1_add (data) {
            geo_json_729357318759c22fdacfcf1a3fb204a1
                .addData(data);
        }
            geo_json_729357318759c22fdacfcf1a3fb204a1_add({"features": [{"geometry": {"coordinates": [[-79.540904, 43.84761], [-79.553825, 43.845763], [-79.556489, 43.84532], [-79.560167, 43.845018], [-79.567416, 43.84362], [-79.571313, 43.842827], [-79.575918, 43.839615], [-79.576148, 43.837537], [-79.577432, 43.833918], [-79.579582, 43.833789], [-79.58338, 43.833043], [-79.586173, 43.839563], [-79.581976, 43.840486]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_729357318759c22fdacfcf1a3fb204a1.bindTooltip(
                `<div>
                     4 MAJOR MACKENZIE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_729357318759c22fdacfcf1a3fb204a1.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_552c2ed91fadc0f9956a9166105ae2c8_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#496E6E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_552c2ed91fadc0f9956a9166105ae2c8_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_552c2ed91fadc0f9956a9166105ae2c8 = L.geoJson(null, {
                onEachFeature: geo_json_552c2ed91fadc0f9956a9166105ae2c8_onEachFeature,
            
                style: geo_json_552c2ed91fadc0f9956a9166105ae2c8_styler,
            ...{
}
        });

        function geo_json_552c2ed91fadc0f9956a9166105ae2c8_add (data) {
            geo_json_552c2ed91fadc0f9956a9166105ae2c8
                .addData(data);
        }
            geo_json_552c2ed91fadc0f9956a9166105ae2c8_add({"features": [{"geometry": {"coordinates": [[-79.471157, 43.797406], [-79.469322, 43.797794], [-79.466937, 43.798697], [-79.464827, 43.800394], [-79.460335, 43.802128], [-79.458114, 43.801931], [-79.454098, 43.802232], [-79.451552, 43.802786], [-79.447408, 43.80359], [-79.445075, 43.804005], [-79.440044, 43.804899], [-79.437017, 43.805531], [-79.433292, 43.806408], [-79.427322, 43.806892], [-79.422827, 43.806933], [-79.422211, 43.805597], [-79.4213, 43.802036], [-79.420274, 43.798244], [-79.420037, 43.797434], [-79.419718, 43.796088], [-79.419191, 43.793992], [-79.418625, 43.791289], [-79.418069, 43.789452], [-79.417496, 43.7872], [-79.415305, 43.782503]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_552c2ed91fadc0f9956a9166105ae2c8.bindTooltip(
                `<div>
                     5 CLARK
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_552c2ed91fadc0f9956a9166105ae2c8.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_5450e6082efc79bfc9035505c14f3406_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#496E6E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_5450e6082efc79bfc9035505c14f3406_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_5450e6082efc79bfc9035505c14f3406 = L.geoJson(null, {
                onEachFeature: geo_json_5450e6082efc79bfc9035505c14f3406_onEachFeature,
            
                style: geo_json_5450e6082efc79bfc9035505c14f3406_styler,
            ...{
}
        });

        function geo_json_5450e6082efc79bfc9035505c14f3406_add (data) {
            geo_json_5450e6082efc79bfc9035505c14f3406
                .addData(data);
        }
            geo_json_5450e6082efc79bfc9035505c14f3406_add({"features": [{"geometry": {"coordinates": [[-79.415305, 43.782503], [-79.416698, 43.78496], [-79.417335, 43.787532], [-79.417977, 43.790138], [-79.418316, 43.79149], [-79.418994, 43.794272], [-79.42011, 43.798695], [-79.420878, 43.801684], [-79.423692, 43.806919], [-79.426676, 43.806887], [-79.432699, 43.806692], [-79.437772, 43.805606], [-79.440512, 43.805047], [-79.444741, 43.804204], [-79.449365, 43.803492], [-79.451124, 43.803107], [-79.454968, 43.802215], [-79.457324, 43.802068], [-79.460446, 43.802265], [-79.46458, 43.800809], [-79.466547, 43.799149], [-79.468905, 43.798071], [-79.471012, 43.797623], [-79.472119, 43.794963], [-79.471912, 43.792423], [-79.47387, 43.792447], [-79.476335, 43.791888], [-79.478103, 43.791498], [-79.48221, 43.791331], [-79.481206, 43.7942], [-79.480754, 43.796178], [-79.479099, 43.797755], [-79.478221, 43.799023], [-79.476744, 43.800613], [-79.473661, 43.801302], [-79.47302, 43.798762], [-79.471157, 43.797406]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_5450e6082efc79bfc9035505c14f3406.bindTooltip(
                `<div>
                     5 CLARK
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_5450e6082efc79bfc9035505c14f3406.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_0dc2db7dd4bb7ac3ec6fefcc5da2ea91_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#496E6E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_0dc2db7dd4bb7ac3ec6fefcc5da2ea91_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_0dc2db7dd4bb7ac3ec6fefcc5da2ea91 = L.geoJson(null, {
                onEachFeature: geo_json_0dc2db7dd4bb7ac3ec6fefcc5da2ea91_onEachFeature,
            
                style: geo_json_0dc2db7dd4bb7ac3ec6fefcc5da2ea91_styler,
            ...{
}
        });

        function geo_json_0dc2db7dd4bb7ac3ec6fefcc5da2ea91_add (data) {
            geo_json_0dc2db7dd4bb7ac3ec6fefcc5da2ea91
                .addData(data);
        }
            geo_json_0dc2db7dd4bb7ac3ec6fefcc5da2ea91_add({"features": [{"geometry": {"coordinates": [[-79.474139, 43.801692], [-79.476885, 43.800709], [-79.478377, 43.799094], [-79.479231, 43.797843], [-79.480969, 43.796156], [-79.481792, 43.793753], [-79.482822, 43.791647], [-79.478003, 43.791409], [-79.47594, 43.791853], [-79.473873, 43.792329], [-79.4724, 43.792264], [-79.471432, 43.793155], [-79.471675, 43.794345], [-79.472253, 43.79695], [-79.471157, 43.797406], [-79.469322, 43.797794], [-79.466937, 43.798697], [-79.464827, 43.800394], [-79.460335, 43.802128], [-79.458114, 43.801931], [-79.454098, 43.802232], [-79.451552, 43.802786], [-79.447408, 43.80359], [-79.445075, 43.804005], [-79.440044, 43.804899], [-79.437017, 43.805531], [-79.433292, 43.806408], [-79.427322, 43.806892], [-79.422827, 43.806933], [-79.422211, 43.805597], [-79.4213, 43.802036], [-79.420274, 43.798244], [-79.420037, 43.797434], [-79.419718, 43.796088], [-79.419191, 43.793992], [-79.418625, 43.791289], [-79.418069, 43.789452], [-79.417496, 43.7872], [-79.415305, 43.782503]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_0dc2db7dd4bb7ac3ec6fefcc5da2ea91.bindTooltip(
                `<div>
                     5 CLARK
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_0dc2db7dd4bb7ac3ec6fefcc5da2ea91.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_4031e9294843ccee9bae575de26e3866_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#496E6E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_4031e9294843ccee9bae575de26e3866_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_4031e9294843ccee9bae575de26e3866 = L.geoJson(null, {
                onEachFeature: geo_json_4031e9294843ccee9bae575de26e3866_onEachFeature,
            
                style: geo_json_4031e9294843ccee9bae575de26e3866_styler,
            ...{
}
        });

        function geo_json_4031e9294843ccee9bae575de26e3866_add (data) {
            geo_json_4031e9294843ccee9bae575de26e3866
                .addData(data);
        }
            geo_json_4031e9294843ccee9bae575de26e3866_add({"features": [{"geometry": {"coordinates": [[-79.471912, 43.792423], [-79.47387, 43.792447], [-79.476335, 43.791888], [-79.478103, 43.791498], [-79.48221, 43.791331], [-79.481206, 43.7942], [-79.480754, 43.796178], [-79.479099, 43.797755], [-79.478221, 43.799023], [-79.476744, 43.800613]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_4031e9294843ccee9bae575de26e3866.bindTooltip(
                `<div>
                     5 CLARK
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_4031e9294843ccee9bae575de26e3866.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_259fa5f8f2c069a75346b42ea759e142_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#496E6E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_259fa5f8f2c069a75346b42ea759e142_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_259fa5f8f2c069a75346b42ea759e142 = L.geoJson(null, {
                onEachFeature: geo_json_259fa5f8f2c069a75346b42ea759e142_onEachFeature,
            
                style: geo_json_259fa5f8f2c069a75346b42ea759e142_styler,
            ...{
}
        });

        function geo_json_259fa5f8f2c069a75346b42ea759e142_add (data) {
            geo_json_259fa5f8f2c069a75346b42ea759e142
                .addData(data);
        }
            geo_json_259fa5f8f2c069a75346b42ea759e142_add({"features": [{"geometry": {"coordinates": [[-79.415305, 43.782503], [-79.416698, 43.78496], [-79.417335, 43.787532], [-79.417977, 43.790138], [-79.418316, 43.79149], [-79.418994, 43.794272], [-79.42011, 43.798695], [-79.420878, 43.801684], [-79.423692, 43.806919], [-79.426676, 43.806887], [-79.432699, 43.806692], [-79.437772, 43.805606], [-79.440512, 43.805047], [-79.444741, 43.804204], [-79.449365, 43.803492], [-79.451124, 43.803107], [-79.454968, 43.802215], [-79.457324, 43.802068], [-79.460446, 43.802265], [-79.46458, 43.800809], [-79.466547, 43.799149], [-79.468905, 43.798071], [-79.471012, 43.797623], [-79.472711, 43.798891], [-79.474139, 43.801692]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_259fa5f8f2c069a75346b42ea759e142.bindTooltip(
                `<div>
                     5 CLARK
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_259fa5f8f2c069a75346b42ea759e142.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_c3734c8340fcf66402dc8dbe0247ac71_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#496E6E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_c3734c8340fcf66402dc8dbe0247ac71_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_c3734c8340fcf66402dc8dbe0247ac71 = L.geoJson(null, {
                onEachFeature: geo_json_c3734c8340fcf66402dc8dbe0247ac71_onEachFeature,
            
                style: geo_json_c3734c8340fcf66402dc8dbe0247ac71_styler,
            ...{
}
        });

        function geo_json_c3734c8340fcf66402dc8dbe0247ac71_add (data) {
            geo_json_c3734c8340fcf66402dc8dbe0247ac71
                .addData(data);
        }
            geo_json_c3734c8340fcf66402dc8dbe0247ac71_add({"features": [{"geometry": {"coordinates": [[-79.415305, 43.782503], [-79.416698, 43.78496], [-79.417335, 43.787532], [-79.417977, 43.790138], [-79.418316, 43.79149], [-79.418994, 43.794272], [-79.42011, 43.798695], [-79.420878, 43.801684], [-79.423692, 43.806919], [-79.426676, 43.806887], [-79.432699, 43.806692], [-79.437772, 43.805606], [-79.440512, 43.805047], [-79.444741, 43.804204], [-79.449365, 43.803492], [-79.451124, 43.803107], [-79.454968, 43.802215], [-79.457324, 43.802068], [-79.460446, 43.802265], [-79.46458, 43.800809], [-79.466547, 43.799149], [-79.468905, 43.798071], [-79.471012, 43.797623], [-79.472119, 43.794963], [-79.471912, 43.792423]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_c3734c8340fcf66402dc8dbe0247ac71.bindTooltip(
                `<div>
                     5 CLARK
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_c3734c8340fcf66402dc8dbe0247ac71.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_cdd3a4428fed0cf742fde56e6c3d3a84_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0058A9", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_cdd3a4428fed0cf742fde56e6c3d3a84_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_cdd3a4428fed0cf742fde56e6c3d3a84 = L.geoJson(null, {
                onEachFeature: geo_json_cdd3a4428fed0cf742fde56e6c3d3a84_onEachFeature,
            
                style: geo_json_cdd3a4428fed0cf742fde56e6c3d3a84_styler,
            ...{
}
        });

        function geo_json_cdd3a4428fed0cf742fde56e6c3d3a84_add (data) {
            geo_json_cdd3a4428fed0cf742fde56e6c3d3a84
                .addData(data);
        }
            geo_json_cdd3a4428fed0cf742fde56e6c3d3a84_add({"features": [{"geometry": {"coordinates": [[-79.604677, 43.729119], [-79.60646, 43.730781], [-79.608936, 43.73214], [-79.609349, 43.733981], [-79.606904, 43.73369], [-79.603868, 43.733918], [-79.601172, 43.734556], [-79.59507, 43.735917], [-79.591781, 43.737271], [-79.593836, 43.74153], [-79.595195, 43.744254], [-79.598395, 43.750847], [-79.599891, 43.753954], [-79.601594, 43.756009], [-79.603845, 43.758523], [-79.606115, 43.762939], [-79.607071, 43.766824], [-79.607565, 43.769042], [-79.608515, 43.772903], [-79.609193, 43.775647], [-79.609866, 43.777783], [-79.610555, 43.78081], [-79.610659, 43.783703], [-79.61131, 43.785272], [-79.611916, 43.786659], [-79.613012, 43.789375], [-79.615866, 43.790929], [-79.620413, 43.791815], [-79.621838, 43.791352], [-79.623201, 43.788798], [-79.622442, 43.784712], [-79.623976, 43.784328], [-79.625133, 43.788107], [-79.625923, 43.791294], [-79.62039, 43.793749], [-79.6191, 43.798426], [-79.622507, 43.800516], [-79.62528, 43.800884], [-79.628141, 43.800314], [-79.628762, 43.806205], [-79.628824, 43.810888], [-79.616653, 43.813203], [-79.61133, 43.814407], [-79.606169, 43.81555], [-79.600366, 43.816914], [-79.597969, 43.816642]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_cdd3a4428fed0cf742fde56e6c3d3a84.bindTooltip(
                `<div>
                     7 MARTIN GROVE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_cdd3a4428fed0cf742fde56e6c3d3a84.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_28ce8ee46b0161013a9cdfa5eaf00097_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0058A9", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_28ce8ee46b0161013a9cdfa5eaf00097_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_28ce8ee46b0161013a9cdfa5eaf00097 = L.geoJson(null, {
                onEachFeature: geo_json_28ce8ee46b0161013a9cdfa5eaf00097_onEachFeature,
            
                style: geo_json_28ce8ee46b0161013a9cdfa5eaf00097_styler,
            ...{
}
        });

        function geo_json_28ce8ee46b0161013a9cdfa5eaf00097_add (data) {
            geo_json_28ce8ee46b0161013a9cdfa5eaf00097
                .addData(data);
        }
            geo_json_28ce8ee46b0161013a9cdfa5eaf00097_add({"features": [{"geometry": {"coordinates": [[-79.597969, 43.816642], [-79.601983, 43.816775], [-79.605667, 43.81591], [-79.610958, 43.814749], [-79.616104, 43.81353], [-79.629063, 43.810667], [-79.629071, 43.806527], [-79.627342, 43.800252], [-79.62579, 43.800621], [-79.622089, 43.800231], [-79.619269, 43.798772], [-79.620649, 43.793885], [-79.62473, 43.79203], [-79.625483, 43.788469], [-79.622979, 43.784315], [-79.623077, 43.788459], [-79.620365, 43.791728], [-79.619683, 43.791768], [-79.6163, 43.790722], [-79.612978, 43.788753], [-79.612323, 43.7872], [-79.611459, 43.7851], [-79.610704, 43.783252], [-79.610723, 43.780646], [-79.610062, 43.777678], [-79.609657, 43.77622], [-79.608952, 43.773341], [-79.607978, 43.769348], [-79.607428, 43.767299], [-79.606311, 43.762821], [-79.605065, 43.759554], [-79.603776, 43.758056], [-79.601838, 43.756097], [-79.600281, 43.754169], [-79.59883, 43.751089], [-79.595533, 43.744396], [-79.594606, 43.742463], [-79.592473, 43.736709], [-79.594771, 43.736166], [-79.60063, 43.734865], [-79.604114, 43.734046], [-79.606432, 43.733806], [-79.61012, 43.733745], [-79.608903, 43.731829], [-79.606945, 43.730756], [-79.604677, 43.729119]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_28ce8ee46b0161013a9cdfa5eaf00097.bindTooltip(
                `<div>
                     7 MARTIN GROVE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_28ce8ee46b0161013a9cdfa5eaf00097.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_5f198f4e8b5bc4e45b3b9da1dc0ee7d2_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0058A9", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_5f198f4e8b5bc4e45b3b9da1dc0ee7d2_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_5f198f4e8b5bc4e45b3b9da1dc0ee7d2 = L.geoJson(null, {
                onEachFeature: geo_json_5f198f4e8b5bc4e45b3b9da1dc0ee7d2_onEachFeature,
            
                style: geo_json_5f198f4e8b5bc4e45b3b9da1dc0ee7d2_styler,
            ...{
}
        });

        function geo_json_5f198f4e8b5bc4e45b3b9da1dc0ee7d2_add (data) {
            geo_json_5f198f4e8b5bc4e45b3b9da1dc0ee7d2
                .addData(data);
        }
            geo_json_5f198f4e8b5bc4e45b3b9da1dc0ee7d2_add({"features": [{"geometry": {"coordinates": [[-79.6029, 43.72053], [-79.601552, 43.722803], [-79.604114, 43.734046], [-79.606432, 43.733806], [-79.608903, 43.731829], [-79.606945, 43.730756], [-79.604677, 43.729119], [-79.60646, 43.730781], [-79.608936, 43.73214], [-79.609349, 43.733981], [-79.606904, 43.73369], [-79.603868, 43.733918], [-79.601172, 43.734556], [-79.59507, 43.735917], [-79.591781, 43.737271], [-79.593836, 43.74153], [-79.595195, 43.744254], [-79.598395, 43.750847], [-79.599891, 43.753954], [-79.601594, 43.756009], [-79.603845, 43.758523], [-79.606115, 43.762939], [-79.607071, 43.766824], [-79.607565, 43.769042], [-79.608515, 43.772903], [-79.609193, 43.775647], [-79.609866, 43.777783], [-79.610555, 43.78081], [-79.610659, 43.783703], [-79.61131, 43.785272], [-79.611916, 43.786659], [-79.613012, 43.789375], [-79.615866, 43.790929], [-79.620413, 43.791815], [-79.621838, 43.791352], [-79.623201, 43.788798], [-79.622442, 43.784712], [-79.623976, 43.784328], [-79.625133, 43.788107], [-79.625923, 43.791294], [-79.62039, 43.793749], [-79.6191, 43.798426], [-79.622507, 43.800516], [-79.62528, 43.800884], [-79.628141, 43.800314], [-79.628762, 43.806205], [-79.628824, 43.810888], [-79.616653, 43.813203], [-79.61133, 43.814407], [-79.606169, 43.81555], [-79.600366, 43.816914], [-79.597969, 43.816642]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_5f198f4e8b5bc4e45b3b9da1dc0ee7d2.bindTooltip(
                `<div>
                     7 MARTIN GROVE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_5f198f4e8b5bc4e45b3b9da1dc0ee7d2.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_a2b30650ae87a23251dad0cc61cdf2a4_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0058A9", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_a2b30650ae87a23251dad0cc61cdf2a4_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_a2b30650ae87a23251dad0cc61cdf2a4 = L.geoJson(null, {
                onEachFeature: geo_json_a2b30650ae87a23251dad0cc61cdf2a4_onEachFeature,
            
                style: geo_json_a2b30650ae87a23251dad0cc61cdf2a4_styler,
            ...{
}
        });

        function geo_json_a2b30650ae87a23251dad0cc61cdf2a4_add (data) {
            geo_json_a2b30650ae87a23251dad0cc61cdf2a4
                .addData(data);
        }
            geo_json_a2b30650ae87a23251dad0cc61cdf2a4_add({"features": [{"geometry": {"coordinates": [[-79.597969, 43.816642], [-79.601983, 43.816775], [-79.605667, 43.81591], [-79.610958, 43.814749], [-79.616104, 43.81353], [-79.629063, 43.810667], [-79.629071, 43.806527], [-79.627342, 43.800252], [-79.62579, 43.800621], [-79.622089, 43.800231], [-79.619269, 43.798772], [-79.620649, 43.793885], [-79.62473, 43.79203], [-79.625483, 43.788469], [-79.622979, 43.784315], [-79.623077, 43.788459], [-79.620365, 43.791728], [-79.619683, 43.791768], [-79.6163, 43.790722], [-79.612978, 43.788753], [-79.612323, 43.7872], [-79.611459, 43.7851], [-79.610704, 43.783252], [-79.610723, 43.780646], [-79.610062, 43.777678], [-79.609657, 43.77622], [-79.608952, 43.773341], [-79.607978, 43.769348], [-79.607428, 43.767299], [-79.606311, 43.762821], [-79.605065, 43.759554], [-79.603776, 43.758056], [-79.601838, 43.756097], [-79.600281, 43.754169], [-79.59883, 43.751089], [-79.595533, 43.744396], [-79.594606, 43.742463], [-79.592473, 43.736709], [-79.594771, 43.736166], [-79.60063, 43.734865], [-79.604114, 43.734046], [-79.606432, 43.733806], [-79.61012, 43.733745], [-79.608903, 43.731829], [-79.606945, 43.730756], [-79.604677, 43.729119], [-79.60646, 43.730781], [-79.608936, 43.73214], [-79.609349, 43.733981], [-79.606904, 43.73369], [-79.603868, 43.733918], [-79.598064, 43.722135], [-79.6029, 43.72053]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_a2b30650ae87a23251dad0cc61cdf2a4.bindTooltip(
                `<div>
                     7 MARTIN GROVE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_a2b30650ae87a23251dad0cc61cdf2a4.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_75ca702e55a7638d35098dfe37362850_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#2A2A86", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_75ca702e55a7638d35098dfe37362850_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_75ca702e55a7638d35098dfe37362850 = L.geoJson(null, {
                onEachFeature: geo_json_75ca702e55a7638d35098dfe37362850_onEachFeature,
            
                style: geo_json_75ca702e55a7638d35098dfe37362850_styler,
            ...{
}
        });

        function geo_json_75ca702e55a7638d35098dfe37362850_add (data) {
            geo_json_75ca702e55a7638d35098dfe37362850
                .addData(data);
        }
            geo_json_75ca702e55a7638d35098dfe37362850_add({"features": [{"geometry": {"coordinates": [[-79.30734, 43.823929], [-79.29984, 43.82555], [-79.30265, 43.82485], [-79.308041, 43.823597], [-79.311865, 43.822705], [-79.310654, 43.823769], [-79.310773, 43.826202], [-79.309453, 43.828283], [-79.307108, 43.828953], [-79.305535, 43.832129], [-79.304375, 43.834217], [-79.303474, 43.838479], [-79.304106, 43.840864], [-79.30471, 43.843316], [-79.30548, 43.845964], [-79.308448, 43.853611], [-79.31081, 43.853074], [-79.313954, 43.852154], [-79.311234, 43.852767], [-79.309213, 43.85326], [-79.306261, 43.854747], [-79.305354, 43.855789], [-79.303456, 43.857799], [-79.302588, 43.859408], [-79.303396, 43.862411], [-79.303919, 43.866377], [-79.304843, 43.869851], [-79.306028, 43.872688], [-79.309673, 43.875844], [-79.312689, 43.876842], [-79.31419, 43.8799], [-79.314435, 43.881422], [-79.31543, 43.884984], [-79.316355, 43.888251], [-79.315666, 43.888557], [-79.312012, 43.889341], [-79.310452, 43.889737], [-79.310087, 43.891759], [-79.311592, 43.893656], [-79.312512, 43.89497], [-79.313444, 43.89714], [-79.318684, 43.896336], [-79.320831, 43.8969]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_75ca702e55a7638d35098dfe37362850.bindTooltip(
                `<div>
                     8 KENNEDY
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_75ca702e55a7638d35098dfe37362850.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_a41f765d0813725752e1cf67db087f4b_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#2A2A86", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_a41f765d0813725752e1cf67db087f4b_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_a41f765d0813725752e1cf67db087f4b = L.geoJson(null, {
                onEachFeature: geo_json_a41f765d0813725752e1cf67db087f4b_onEachFeature,
            
                style: geo_json_a41f765d0813725752e1cf67db087f4b_styler,
            ...{
}
        });

        function geo_json_a41f765d0813725752e1cf67db087f4b_add (data) {
            geo_json_a41f765d0813725752e1cf67db087f4b
                .addData(data);
        }
            geo_json_a41f765d0813725752e1cf67db087f4b_add({"features": [{"geometry": {"coordinates": [[-79.303634, 43.86215], [-79.302821, 43.859806], [-79.303326, 43.858309], [-79.305193, 43.856339], [-79.307565, 43.853652], [-79.308448, 43.853611], [-79.31081, 43.853074], [-79.314196, 43.852113], [-79.311234, 43.852767], [-79.309213, 43.85326], [-79.305834, 43.846266], [-79.305136, 43.843729], [-79.304506, 43.841191], [-79.303896, 43.838848], [-79.304433, 43.834733], [-79.305563, 43.832618], [-79.307974, 43.827974], [-79.307529, 43.82435]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_a41f765d0813725752e1cf67db087f4b.bindTooltip(
                `<div>
                     8 KENNEDY
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_a41f765d0813725752e1cf67db087f4b.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_eb2e0be7fc33199d58007896e6cc5ca6_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#2A2A86", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_eb2e0be7fc33199d58007896e6cc5ca6_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_eb2e0be7fc33199d58007896e6cc5ca6 = L.geoJson(null, {
                onEachFeature: geo_json_eb2e0be7fc33199d58007896e6cc5ca6_onEachFeature,
            
                style: geo_json_eb2e0be7fc33199d58007896e6cc5ca6_styler,
            ...{
}
        });

        function geo_json_eb2e0be7fc33199d58007896e6cc5ca6_add (data) {
            geo_json_eb2e0be7fc33199d58007896e6cc5ca6
                .addData(data);
        }
            geo_json_eb2e0be7fc33199d58007896e6cc5ca6_add({"features": [{"geometry": {"coordinates": [[-79.320831, 43.8969], [-79.319462, 43.897339], [-79.318684, 43.896336], [-79.318239, 43.894256], [-79.317552, 43.891385], [-79.31676, 43.888633], [-79.315923, 43.885384], [-79.31512, 43.882335], [-79.314525, 43.879725], [-79.313194, 43.876942], [-79.310302, 43.875764], [-79.306172, 43.872554], [-79.305333, 43.87022], [-79.304154, 43.866752], [-79.303634, 43.86215], [-79.302821, 43.859806], [-79.303326, 43.858309], [-79.305193, 43.856339], [-79.307565, 43.853652], [-79.308448, 43.853611], [-79.31081, 43.853074], [-79.314196, 43.852113], [-79.311234, 43.852767], [-79.309213, 43.85326], [-79.305834, 43.846266], [-79.305136, 43.843729], [-79.304506, 43.841191], [-79.303896, 43.838848], [-79.304433, 43.834733], [-79.305563, 43.832618], [-79.307974, 43.827974], [-79.307529, 43.82435]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_eb2e0be7fc33199d58007896e6cc5ca6.bindTooltip(
                `<div>
                     8 KENNEDY
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_eb2e0be7fc33199d58007896e6cc5ca6.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_6615eb10abb145988984d1601d802e64_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#2A2A86", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_6615eb10abb145988984d1601d802e64_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_6615eb10abb145988984d1601d802e64 = L.geoJson(null, {
                onEachFeature: geo_json_6615eb10abb145988984d1601d802e64_onEachFeature,
            
                style: geo_json_6615eb10abb145988984d1601d802e64_styler,
            ...{
}
        });

        function geo_json_6615eb10abb145988984d1601d802e64_add (data) {
            geo_json_6615eb10abb145988984d1601d802e64
                .addData(data);
        }
            geo_json_6615eb10abb145988984d1601d802e64_add({"features": [{"geometry": {"coordinates": [[-79.320831, 43.8969], [-79.319462, 43.897339], [-79.318684, 43.896336], [-79.318239, 43.894256], [-79.317552, 43.891385], [-79.31676, 43.888633], [-79.315923, 43.885384], [-79.31512, 43.882335], [-79.314525, 43.879725], [-79.313194, 43.876942], [-79.310302, 43.875764], [-79.306172, 43.872554], [-79.305333, 43.87022], [-79.304154, 43.866752], [-79.303634, 43.86215], [-79.302821, 43.859806], [-79.303326, 43.858309], [-79.305193, 43.856339], [-79.307565, 43.853652], [-79.308448, 43.853611], [-79.31081, 43.853074], [-79.314196, 43.852113], [-79.311234, 43.852767], [-79.309213, 43.85326], [-79.305834, 43.846266], [-79.305136, 43.843729], [-79.304506, 43.841191], [-79.303896, 43.838848], [-79.304433, 43.834733], [-79.305563, 43.832618], [-79.307974, 43.827974], [-79.307529, 43.82435], [-79.29984, 43.82555], [-79.30265, 43.82485], [-79.308041, 43.823597], [-79.311865, 43.822705], [-79.310654, 43.823769], [-79.310773, 43.826202], [-79.309453, 43.828283]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_6615eb10abb145988984d1601d802e64.bindTooltip(
                `<div>
                     8 KENNEDY
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_6615eb10abb145988984d1601d802e64.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_edbaad0709ca8dc45d7bdf131a9d795e_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#2A2A86", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_edbaad0709ca8dc45d7bdf131a9d795e_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_edbaad0709ca8dc45d7bdf131a9d795e = L.geoJson(null, {
                onEachFeature: geo_json_edbaad0709ca8dc45d7bdf131a9d795e_onEachFeature,
            
                style: geo_json_edbaad0709ca8dc45d7bdf131a9d795e_styler,
            ...{
}
        });

        function geo_json_edbaad0709ca8dc45d7bdf131a9d795e_add (data) {
            geo_json_edbaad0709ca8dc45d7bdf131a9d795e
                .addData(data);
        }
            geo_json_edbaad0709ca8dc45d7bdf131a9d795e_add({"features": [{"geometry": {"coordinates": [[-79.303396, 43.862411], [-79.303919, 43.866377], [-79.304843, 43.869851], [-79.306028, 43.872688], [-79.309673, 43.875844], [-79.312689, 43.876842], [-79.31419, 43.8799], [-79.314435, 43.881422], [-79.31543, 43.884984], [-79.316355, 43.888251], [-79.315666, 43.888557], [-79.312012, 43.889341], [-79.310452, 43.889737], [-79.310087, 43.891759], [-79.311592, 43.893656], [-79.312512, 43.89497], [-79.313444, 43.89714], [-79.318684, 43.896336], [-79.320831, 43.8969]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_edbaad0709ca8dc45d7bdf131a9d795e.bindTooltip(
                `<div>
                     8 KENNEDY
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_edbaad0709ca8dc45d7bdf131a9d795e.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_10826b05e7c69495c2bdbd82e74a3921_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#F58220", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_10826b05e7c69495c2bdbd82e74a3921_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_10826b05e7c69495c2bdbd82e74a3921 = L.geoJson(null, {
                onEachFeature: geo_json_10826b05e7c69495c2bdbd82e74a3921_onEachFeature,
            
                style: geo_json_10826b05e7c69495c2bdbd82e74a3921_styler,
            ...{
}
        });

        function geo_json_10826b05e7c69495c2bdbd82e74a3921_add (data) {
            geo_json_10826b05e7c69495c2bdbd82e74a3921
                .addData(data);
        }
            geo_json_10826b05e7c69495c2bdbd82e74a3921_add({"features": [{"geometry": {"coordinates": [[-79.227079, 43.864747], [-79.228887, 43.865279], [-79.230636, 43.865957], [-79.232671, 43.868936], [-79.23386, 43.875474], [-79.234601, 43.878512], [-79.235156, 43.880494], [-79.23182, 43.881109], [-79.235961, 43.883962], [-79.237043, 43.888326], [-79.237906, 43.891424], [-79.238615, 43.894395], [-79.239368, 43.897522], [-79.239967, 43.899888], [-79.240465, 43.902051], [-79.240643, 43.904857], [-79.243825, 43.91529], [-79.244991, 43.919984], [-79.246432, 43.925673], [-79.248152, 43.932974], [-79.249689, 43.939015], [-79.252392, 43.950602], [-79.253383, 43.95487], [-79.251185, 43.955606], [-79.248781, 43.957105], [-79.245769, 43.958681], [-79.242335, 43.959183], [-79.241966, 43.960949], [-79.243212, 43.964791], [-79.240405, 43.966507], [-79.236421, 43.966607], [-79.234945, 43.966841], [-79.232186, 43.967423], [-79.230514, 43.968598], [-79.231079, 43.97095], [-79.232892, 43.974523], [-79.238029, 43.973404], [-79.243459, 43.972184], [-79.246891, 43.971391], [-79.249993, 43.970707], [-79.25405, 43.969808], [-79.256705, 43.969241], [-79.260017, 43.968513], [-79.265058, 43.967462], [-79.27014, 43.966374], [-79.274293, 43.965375], [-79.275736, 43.96949], [-79.271618, 43.971009], [-79.26731, 43.972838], [-79.262574, 43.974287], [-79.259437, 43.974932], [-79.257459, 43.975373], [-79.256749, 43.97329], [-79.256311, 43.971165], [-79.256552, 43.967389], [-79.257832, 43.966728], [-79.255956, 43.964805], [-79.255462, 43.9625], [-79.259168, 43.961694], [-79.262449, 43.960802], [-79.265559, 43.96005], [-79.273626, 43.95533]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_10826b05e7c69495c2bdbd82e74a3921.bindTooltip(
                `<div>
                     9 NINTH LINE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_10826b05e7c69495c2bdbd82e74a3921.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_9481d6a44da8ce50856fd64fdd99ad28_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#F58220", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_9481d6a44da8ce50856fd64fdd99ad28_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_9481d6a44da8ce50856fd64fdd99ad28 = L.geoJson(null, {
                onEachFeature: geo_json_9481d6a44da8ce50856fd64fdd99ad28_onEachFeature,
            
                style: geo_json_9481d6a44da8ce50856fd64fdd99ad28_styler,
            ...{
}
        });

        function geo_json_9481d6a44da8ce50856fd64fdd99ad28_add (data) {
            geo_json_9481d6a44da8ce50856fd64fdd99ad28
                .addData(data);
        }
            geo_json_9481d6a44da8ce50856fd64fdd99ad28_add({"features": [{"geometry": {"coordinates": [[-79.273626, 43.95533], [-79.278084, 43.953637], [-79.279128, 43.956556], [-79.276342, 43.9573], [-79.266333, 43.959696], [-79.258688, 43.961599], [-79.255661, 43.964804], [-79.257832, 43.966728], [-79.256331, 43.967054], [-79.256775, 43.968972], [-79.256013, 43.970758], [-79.256388, 43.972489], [-79.259495, 43.975087], [-79.263129, 43.97447], [-79.267602, 43.973048], [-79.271145, 43.971364], [-79.275406, 43.97021], [-79.270837, 43.965929], [-79.26591, 43.966978], [-79.260462, 43.968183], [-79.257053, 43.968999], [-79.254154, 43.969651], [-79.250589, 43.97045], [-79.247062, 43.971241], [-79.243772, 43.971957], [-79.238586, 43.973132], [-79.233781, 43.974219], [-79.232185, 43.974566], [-79.231286, 43.971253], [-79.230573, 43.968019], [-79.234686, 43.967036], [-79.237164, 43.966887], [-79.24096, 43.966279], [-79.243354, 43.964823], [-79.242505, 43.961436], [-79.242115, 43.959595], [-79.244733, 43.958737], [-79.246308, 43.958786], [-79.248884, 43.957196], [-79.251481, 43.955652], [-79.249904, 43.939081], [-79.248753, 43.933546], [-79.246719, 43.925651], [-79.245332, 43.919986], [-79.244356, 43.91596], [-79.241082, 43.905538], [-79.240829, 43.902566], [-79.2404, 43.900311], [-79.239793, 43.897885], [-79.238995, 43.894803], [-79.238255, 43.891857], [-79.237438, 43.888719], [-79.237123, 43.887206], [-79.236317, 43.884493], [-79.23182, 43.881109], [-79.235086, 43.879252], [-79.234766, 43.878138], [-79.234261, 43.875921], [-79.232566, 43.868316], [-79.229899, 43.865284], [-79.227634, 43.864694], [-79.2252, 43.86252], [-79.224469, 43.861015], [-79.223915, 43.85949], [-79.222375, 43.857421], [-79.225124, 43.856733], [-79.228948, 43.855739], [-79.229979, 43.85942], [-79.224746, 43.86225], [-79.227079, 43.864747]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_9481d6a44da8ce50856fd64fdd99ad28.bindTooltip(
                `<div>
                     9 NINTH LINE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_9481d6a44da8ce50856fd64fdd99ad28.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_833cc28f73b611fbe143bc1eb1d81bb1_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#66A6BC", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_833cc28f73b611fbe143bc1eb1d81bb1_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_833cc28f73b611fbe143bc1eb1d81bb1 = L.geoJson(null, {
                onEachFeature: geo_json_833cc28f73b611fbe143bc1eb1d81bb1_onEachFeature,
            
                style: geo_json_833cc28f73b611fbe143bc1eb1d81bb1_styler,
            ...{
}
        });

        function geo_json_833cc28f73b611fbe143bc1eb1d81bb1_add (data) {
            geo_json_833cc28f73b611fbe143bc1eb1d81bb1
                .addData(data);
        }
            geo_json_833cc28f73b611fbe143bc1eb1d81bb1_add({"features": [{"geometry": {"coordinates": [[-79.61131, 43.785272], [-79.611916, 43.786659], [-79.613012, 43.789375], [-79.615866, 43.790929], [-79.619548, 43.791883], [-79.619933, 43.792832], [-79.616381, 43.793758], [-79.610993, 43.794991], [-79.606903, 43.795848], [-79.604128, 43.794876], [-79.600626, 43.792486], [-79.600093, 43.790238], [-79.59928, 43.786854], [-79.598661, 43.784188], [-79.59608, 43.784097], [-79.594245, 43.784474], [-79.591366, 43.785522], [-79.586503, 43.789346], [-79.584551, 43.791961], [-79.57609, 43.79468], [-79.571916, 43.795134], [-79.56293, 43.795454], [-79.56009, 43.79624], [-79.55573, 43.79729], [-79.55219, 43.79796], [-79.55006, 43.79832], [-79.549115, 43.795768], [-79.5474, 43.79308], [-79.543236, 43.793943], [-79.536652, 43.796195], [-79.53296, 43.796934], [-79.528416, 43.796561]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_833cc28f73b611fbe143bc1eb1d81bb1.bindTooltip(
                `<div>
                     10 WOODBRIDGE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_833cc28f73b611fbe143bc1eb1d81bb1.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_618ace146be5911a08b5c37b96f3d206_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#66A6BC", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_618ace146be5911a08b5c37b96f3d206_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_618ace146be5911a08b5c37b96f3d206 = L.geoJson(null, {
                onEachFeature: geo_json_618ace146be5911a08b5c37b96f3d206_onEachFeature,
            
                style: geo_json_618ace146be5911a08b5c37b96f3d206_styler,
            ...{
}
        });

        function geo_json_618ace146be5911a08b5c37b96f3d206_add (data) {
            geo_json_618ace146be5911a08b5c37b96f3d206
                .addData(data);
        }
            geo_json_618ace146be5911a08b5c37b96f3d206_add({"features": [{"geometry": {"coordinates": [[-79.528416, 43.796561], [-79.532382, 43.797183], [-79.536315, 43.796425], [-79.542911, 43.794356], [-79.54795, 43.793183], [-79.548919, 43.795976], [-79.55034, 43.79848], [-79.55544, 43.79748], [-79.55985, 43.79646], [-79.562286, 43.795687], [-79.567352, 43.795369], [-79.570957, 43.795361], [-79.575443, 43.794897], [-79.58504, 43.79143], [-79.587471, 43.789067], [-79.589097, 43.786845], [-79.59112, 43.785881], [-79.592989, 43.784919], [-79.596285, 43.784175], [-79.598924, 43.783635], [-79.603073, 43.78379], [-79.605793, 43.783265], [-79.609158, 43.782922], [-79.610659, 43.783703], [-79.61131, 43.785272]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_618ace146be5911a08b5c37b96f3d206.bindTooltip(
                `<div>
                     10 WOODBRIDGE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_618ace146be5911a08b5c37b96f3d206.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_fea409f339770a525ac905809ee2f5b3_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#6DC069", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_fea409f339770a525ac905809ee2f5b3_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_fea409f339770a525ac905809ee2f5b3 = L.geoJson(null, {
                onEachFeature: geo_json_fea409f339770a525ac905809ee2f5b3_onEachFeature,
            
                style: geo_json_fea409f339770a525ac905809ee2f5b3_styler,
            ...{
}
        });

        function geo_json_fea409f339770a525ac905809ee2f5b3_add (data) {
            geo_json_fea409f339770a525ac905809ee2f5b3
                .addData(data);
        }
            geo_json_fea409f339770a525ac905809ee2f5b3_add({"features": [{"geometry": {"coordinates": [[-79.576585, 43.764143], [-79.57414, 43.764392], [-79.571296, 43.76501], [-79.565497, 43.767264], [-79.567122, 43.767866], [-79.569366, 43.770074], [-79.571887, 43.77994], [-79.572424, 43.781901], [-79.573197, 43.785061], [-79.573565, 43.786536], [-79.573996, 43.788405], [-79.575223, 43.792853], [-79.575586, 43.794542], [-79.571916, 43.795134], [-79.572029, 43.797446], [-79.571121, 43.799946], [-79.569566, 43.801072], [-79.567666, 43.802189], [-79.564608, 43.802761], [-79.564433, 43.804764], [-79.558164, 43.806528], [-79.552303, 43.80773], [-79.548641, 43.808343], [-79.537876, 43.811166], [-79.538528, 43.812825], [-79.539272, 43.815061], [-79.539161, 43.816977], [-79.538805, 43.820118], [-79.539041, 43.821646], [-79.536888, 43.823275], [-79.53437, 43.827187]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_fea409f339770a525ac905809ee2f5b3.bindTooltip(
                `<div>
                     12 PINE VALLEY
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_fea409f339770a525ac905809ee2f5b3.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_7170cc7c6810910b59fd6dd5eafea649_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#6DC069", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_7170cc7c6810910b59fd6dd5eafea649_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_7170cc7c6810910b59fd6dd5eafea649 = L.geoJson(null, {
                onEachFeature: geo_json_7170cc7c6810910b59fd6dd5eafea649_onEachFeature,
            
                style: geo_json_7170cc7c6810910b59fd6dd5eafea649_styler,
            ...{
}
        });

        function geo_json_7170cc7c6810910b59fd6dd5eafea649_add (data) {
            geo_json_7170cc7c6810910b59fd6dd5eafea649
                .addData(data);
        }
            geo_json_7170cc7c6810910b59fd6dd5eafea649_add({"features": [{"geometry": {"coordinates": [[-79.53437, 43.827187], [-79.537811, 43.823452], [-79.539431, 43.821994], [-79.539089, 43.819659], [-79.53932, 43.817398], [-79.539405, 43.815762], [-79.538582, 43.812499], [-79.537937, 43.810728], [-79.547855, 43.808702], [-79.55157, 43.808107], [-79.557818, 43.806831], [-79.564601, 43.804728], [-79.564192, 43.803008], [-79.568099, 43.802193], [-79.56949, 43.801295], [-79.57127, 43.800026], [-79.572424, 43.797684], [-79.571569, 43.795499], [-79.57579, 43.794333], [-79.57545, 43.793017], [-79.574449, 43.788792], [-79.573847, 43.786758], [-79.573365, 43.784617], [-79.572775, 43.782245], [-79.572106, 43.77976], [-79.569718, 43.770584], [-79.5679, 43.767865], [-79.565273, 43.766913], [-79.571971, 43.765138], [-79.574512, 43.764507], [-79.576585, 43.764143]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_7170cc7c6810910b59fd6dd5eafea649.bindTooltip(
                `<div>
                     12 PINE VALLEY
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_7170cc7c6810910b59fd6dd5eafea649.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_b1ff033e4f6926abcf00ea8b1190883f_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A17D7D", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_b1ff033e4f6926abcf00ea8b1190883f_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_b1ff033e4f6926abcf00ea8b1190883f = L.geoJson(null, {
                onEachFeature: geo_json_b1ff033e4f6926abcf00ea8b1190883f_onEachFeature,
            
                style: geo_json_b1ff033e4f6926abcf00ea8b1190883f_styler,
            ...{
}
        });

        function geo_json_b1ff033e4f6926abcf00ea8b1190883f_add (data) {
            geo_json_b1ff033e4f6926abcf00ea8b1190883f
                .addData(data);
        }
            geo_json_b1ff033e4f6926abcf00ea8b1190883f_add({"features": [{"geometry": {"coordinates": [[-79.576585, 43.764143], [-79.575136, 43.765203], [-79.579212, 43.772344], [-79.58071, 43.775144], [-79.583753, 43.777753], [-79.586222, 43.7791], [-79.588838, 43.780362], [-79.58876, 43.786541], [-79.586503, 43.789346], [-79.584551, 43.791961], [-79.584553, 43.795148], [-79.584636, 43.797703], [-79.584655, 43.798704], [-79.584817, 43.80193], [-79.587014, 43.807111], [-79.58849, 43.809285], [-79.591462, 43.811564], [-79.595645, 43.814299], [-79.597908, 43.815723], [-79.601983, 43.816775], [-79.605667, 43.81591], [-79.610958, 43.814749], [-79.616104, 43.81353], [-79.616569, 43.813884], [-79.618076, 43.814864], [-79.620676, 43.814527], [-79.623266, 43.815483], [-79.62513, 43.81722], [-79.625605, 43.819785], [-79.624827, 43.821181], [-79.622131, 43.822577], [-79.620199, 43.822973], [-79.617296, 43.823517], [-79.614259, 43.824148], [-79.611034, 43.825414], [-79.609719, 43.825861]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_b1ff033e4f6926abcf00ea8b1190883f.bindTooltip(
                `<div>
                     13 ISLINGTON
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_b1ff033e4f6926abcf00ea8b1190883f.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_31decb14009ab516174cf61d01ae6a7b_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A17D7D", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_31decb14009ab516174cf61d01ae6a7b_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_31decb14009ab516174cf61d01ae6a7b = L.geoJson(null, {
                onEachFeature: geo_json_31decb14009ab516174cf61d01ae6a7b_onEachFeature,
            
                style: geo_json_31decb14009ab516174cf61d01ae6a7b_styler,
            ...{
}
        });

        function geo_json_31decb14009ab516174cf61d01ae6a7b_add (data) {
            geo_json_31decb14009ab516174cf61d01ae6a7b
                .addData(data);
        }
            geo_json_31decb14009ab516174cf61d01ae6a7b_add({"features": [{"geometry": {"coordinates": [[-79.597908, 43.815723], [-79.601983, 43.816775], [-79.605667, 43.81591], [-79.610958, 43.814749], [-79.616104, 43.81353], [-79.616569, 43.813884], [-79.618076, 43.814864], [-79.620676, 43.814527], [-79.623266, 43.815483], [-79.62513, 43.81722], [-79.625605, 43.819785], [-79.624827, 43.821181], [-79.622131, 43.822577], [-79.620199, 43.822973], [-79.617296, 43.823517], [-79.614259, 43.824148], [-79.611034, 43.825414], [-79.609719, 43.825861]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_31decb14009ab516174cf61d01ae6a7b.bindTooltip(
                `<div>
                     13 ISLINGTON
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_31decb14009ab516174cf61d01ae6a7b.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_799ac3586fce56aab8b58ec70c3fc9d5_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A17D7D", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_799ac3586fce56aab8b58ec70c3fc9d5_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_799ac3586fce56aab8b58ec70c3fc9d5 = L.geoJson(null, {
                onEachFeature: geo_json_799ac3586fce56aab8b58ec70c3fc9d5_onEachFeature,
            
                style: geo_json_799ac3586fce56aab8b58ec70c3fc9d5_styler,
            ...{
}
        });

        function geo_json_799ac3586fce56aab8b58ec70c3fc9d5_add (data) {
            geo_json_799ac3586fce56aab8b58ec70c3fc9d5
                .addData(data);
        }
            geo_json_799ac3586fce56aab8b58ec70c3fc9d5_add({"features": [{"geometry": {"coordinates": [[-79.609719, 43.825861], [-79.608323, 43.824053], [-79.607108, 43.821969], [-79.603197, 43.818772], [-79.601177, 43.817489], [-79.598627, 43.815883], [-79.596501, 43.814527], [-79.591908, 43.811594], [-79.587466, 43.807328], [-79.585005, 43.801459], [-79.58489, 43.799455], [-79.584798, 43.797414], [-79.584717, 43.795805], [-79.584727, 43.792421], [-79.587471, 43.789067], [-79.589097, 43.786845], [-79.589758, 43.780974], [-79.586868, 43.779221], [-79.584177, 43.777736], [-79.581114, 43.775326], [-79.579416, 43.771617], [-79.575092, 43.764522], [-79.576585, 43.764143]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_799ac3586fce56aab8b58ec70c3fc9d5.bindTooltip(
                `<div>
                     13 ISLINGTON
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_799ac3586fce56aab8b58ec70c3fc9d5.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_32eaad5ec745947b78c7249d0fae286c_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A17D7D", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_32eaad5ec745947b78c7249d0fae286c_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_32eaad5ec745947b78c7249d0fae286c = L.geoJson(null, {
                onEachFeature: geo_json_32eaad5ec745947b78c7249d0fae286c_onEachFeature,
            
                style: geo_json_32eaad5ec745947b78c7249d0fae286c_styler,
            ...{
}
        });

        function geo_json_32eaad5ec745947b78c7249d0fae286c_add (data) {
            geo_json_32eaad5ec745947b78c7249d0fae286c
                .addData(data);
        }
            geo_json_32eaad5ec745947b78c7249d0fae286c_add({"features": [{"geometry": {"coordinates": [[-79.609719, 43.825861], [-79.608323, 43.824053], [-79.607108, 43.821969], [-79.603197, 43.818772], [-79.601177, 43.817489]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_32eaad5ec745947b78c7249d0fae286c.bindTooltip(
                `<div>
                     13 ISLINGTON
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_32eaad5ec745947b78c7249d0fae286c.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_8cb9073032aa1ded090e1a10b3de9125_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#66A6BC", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_8cb9073032aa1ded090e1a10b3de9125_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_8cb9073032aa1ded090e1a10b3de9125 = L.geoJson(null, {
                onEachFeature: geo_json_8cb9073032aa1ded090e1a10b3de9125_onEachFeature,
            
                style: geo_json_8cb9073032aa1ded090e1a10b3de9125_styler,
            ...{
}
        });

        function geo_json_8cb9073032aa1ded090e1a10b3de9125_add (data) {
            geo_json_8cb9073032aa1ded090e1a10b3de9125
                .addData(data);
        }
            geo_json_8cb9073032aa1ded090e1a10b3de9125_add({"features": [{"geometry": {"coordinates": [[-79.350357, 43.822295], [-79.351427, 43.825126], [-79.348855, 43.825845], [-79.345585, 43.82701], [-79.343335, 43.827535], [-79.341632, 43.827824], [-79.340239, 43.828594], [-79.337435, 43.830806], [-79.33567, 43.832256], [-79.332154, 43.83609], [-79.329605, 43.837466], [-79.325154, 43.838562], [-79.320578, 43.839692], [-79.315852, 43.840826], [-79.313131, 43.841489], [-79.311017, 43.842003], [-79.305175, 43.843313], [-79.299114, 43.844693], [-79.294782, 43.845687], [-79.290661, 43.846638], [-79.287349, 43.847432], [-79.284846, 43.847979], [-79.280212, 43.848974], [-79.276134, 43.850084], [-79.272163, 43.851001], [-79.268164, 43.851936], [-79.26306, 43.853139], [-79.258962, 43.854083], [-79.254995, 43.85625], [-79.251469, 43.856335], [-79.249599, 43.858584], [-79.247389, 43.858753], [-79.244804, 43.85819], [-79.243773, 43.856081], [-79.240725, 43.855013], [-79.237612, 43.855779], [-79.237012, 43.858498], [-79.231887, 43.85993], [-79.233443, 43.860308], [-79.234956, 43.861714], [-79.235964, 43.863304], [-79.234752, 43.865388], [-79.2328, 43.86463], [-79.23145, 43.863808], [-79.229191, 43.864961], [-79.227634, 43.864694], [-79.2252, 43.86252], [-79.222541, 43.861204], [-79.218586, 43.86212], [-79.212785, 43.869092], [-79.215888, 43.869834], [-79.220643, 43.870852], [-79.224298, 43.870037], [-79.228283, 43.867323], [-79.229206, 43.865536], [-79.232671, 43.868936], [-79.23386, 43.875474], [-79.234601, 43.878512], [-79.235156, 43.880494], [-79.231813, 43.880902]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_8cb9073032aa1ded090e1a10b3de9125.bindTooltip(
                `<div>
                     14 14TH AVENUE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_8cb9073032aa1ded090e1a10b3de9125.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_9c9d7370c23647b274d2a747fd9c8b9e_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#66A6BC", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_9c9d7370c23647b274d2a747fd9c8b9e_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_9c9d7370c23647b274d2a747fd9c8b9e = L.geoJson(null, {
                onEachFeature: geo_json_9c9d7370c23647b274d2a747fd9c8b9e_onEachFeature,
            
                style: geo_json_9c9d7370c23647b274d2a747fd9c8b9e_styler,
            ...{
}
        });

        function geo_json_9c9d7370c23647b274d2a747fd9c8b9e_add (data) {
            geo_json_9c9d7370c23647b274d2a747fd9c8b9e
                .addData(data);
        }
            geo_json_9c9d7370c23647b274d2a747fd9c8b9e_add({"features": [{"geometry": {"coordinates": [[-79.350357, 43.822295], [-79.351427, 43.825126], [-79.348855, 43.825845], [-79.345585, 43.82701], [-79.343335, 43.827535], [-79.341632, 43.827824], [-79.340239, 43.828594], [-79.337435, 43.830806], [-79.33567, 43.832256], [-79.332154, 43.83609], [-79.329605, 43.837466], [-79.325154, 43.838562], [-79.320578, 43.839692], [-79.315852, 43.840826], [-79.313131, 43.841489], [-79.311017, 43.842003], [-79.305175, 43.843313], [-79.299114, 43.844693], [-79.294782, 43.845687], [-79.290661, 43.846638], [-79.287349, 43.847432], [-79.284846, 43.847979], [-79.280212, 43.848974], [-79.276134, 43.850084], [-79.272163, 43.851001], [-79.268164, 43.851936], [-79.26306, 43.853139], [-79.258962, 43.854083], [-79.254995, 43.85625], [-79.251469, 43.856335], [-79.249599, 43.858584], [-79.247389, 43.858753], [-79.244804, 43.85819], [-79.243773, 43.856081], [-79.240725, 43.855013], [-79.237612, 43.855779], [-79.237012, 43.858498], [-79.231887, 43.85993], [-79.233443, 43.860308], [-79.234956, 43.861714], [-79.240301, 43.861221], [-79.241925, 43.86341], [-79.242542, 43.865355], [-79.24047, 43.865741], [-79.234929, 43.865519], [-79.2328, 43.86463], [-79.23145, 43.863808], [-79.229191, 43.864961], [-79.227634, 43.864694], [-79.2252, 43.86252], [-79.222541, 43.861204], [-79.218586, 43.86212], [-79.212785, 43.869092], [-79.215888, 43.869834], [-79.220643, 43.870852], [-79.224298, 43.870037], [-79.228283, 43.867323], [-79.229206, 43.865536], [-79.232671, 43.868936], [-79.23386, 43.875474], [-79.234601, 43.878512], [-79.235156, 43.880494], [-79.231813, 43.880902]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_9c9d7370c23647b274d2a747fd9c8b9e.bindTooltip(
                `<div>
                     14 14TH AVENUE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_9c9d7370c23647b274d2a747fd9c8b9e.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_52d78c4833fcf0be9e3a8392829cc175_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#66A6BC", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_52d78c4833fcf0be9e3a8392829cc175_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_52d78c4833fcf0be9e3a8392829cc175 = L.geoJson(null, {
                onEachFeature: geo_json_52d78c4833fcf0be9e3a8392829cc175_onEachFeature,
            
                style: geo_json_52d78c4833fcf0be9e3a8392829cc175_styler,
            ...{
}
        });

        function geo_json_52d78c4833fcf0be9e3a8392829cc175_add (data) {
            geo_json_52d78c4833fcf0be9e3a8392829cc175
                .addData(data);
        }
            geo_json_52d78c4833fcf0be9e3a8392829cc175_add({"features": [{"geometry": {"coordinates": [[-79.231813, 43.880902], [-79.235086, 43.879252], [-79.234766, 43.878138], [-79.234261, 43.875921], [-79.232566, 43.868316], [-79.228804, 43.865879], [-79.227586, 43.86825], [-79.224816, 43.869773], [-79.221362, 43.870486], [-79.215883, 43.869552], [-79.212178, 43.868989], [-79.215984, 43.862601], [-79.223979, 43.861102], [-79.224746, 43.86225], [-79.227079, 43.864747], [-79.232257, 43.863842], [-79.232877, 43.864886], [-79.234962, 43.865132], [-79.23604, 43.863676], [-79.235213, 43.861862], [-79.233822, 43.860387], [-79.232184, 43.859921], [-79.23722, 43.857921], [-79.238215, 43.855653], [-79.240491, 43.855191], [-79.243854, 43.856569], [-79.244391, 43.857888], [-79.246777, 43.858916], [-79.249965, 43.858667], [-79.250189, 43.856946], [-79.25245, 43.85628], [-79.255417, 43.856361], [-79.258522, 43.854444], [-79.262234, 43.853479], [-79.267421, 43.852238], [-79.271502, 43.851311], [-79.275633, 43.850338], [-79.27932, 43.849447], [-79.284376, 43.848284], [-79.286767, 43.847702], [-79.290136, 43.846925], [-79.294241, 43.845976], [-79.298558, 43.844984], [-79.30454, 43.843691], [-79.305968, 43.843384], [-79.310594, 43.842347], [-79.313276, 43.841627], [-79.316692, 43.840819], [-79.320125, 43.839981], [-79.324654, 43.838886], [-79.328837, 43.837916], [-79.331952, 43.836686], [-79.335334, 43.832775], [-79.337858, 43.830699], [-79.339843, 43.829145], [-79.34029, 43.827477], [-79.338844, 43.826468], [-79.341402, 43.824133], [-79.344769, 43.823349], [-79.347202, 43.822766], [-79.350357, 43.822295]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_52d78c4833fcf0be9e3a8392829cc175.bindTooltip(
                `<div>
                     14 14TH AVENUE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_52d78c4833fcf0be9e3a8392829cc175.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_dbb9f169a34c38d84b87823565991f27_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#66A6BC", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_dbb9f169a34c38d84b87823565991f27_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_dbb9f169a34c38d84b87823565991f27 = L.geoJson(null, {
                onEachFeature: geo_json_dbb9f169a34c38d84b87823565991f27_onEachFeature,
            
                style: geo_json_dbb9f169a34c38d84b87823565991f27_styler,
            ...{
}
        });

        function geo_json_dbb9f169a34c38d84b87823565991f27_add (data) {
            geo_json_dbb9f169a34c38d84b87823565991f27
                .addData(data);
        }
            geo_json_dbb9f169a34c38d84b87823565991f27_add({"features": [{"geometry": {"coordinates": [[-79.231813, 43.880902], [-79.235086, 43.879252], [-79.234766, 43.878138], [-79.234261, 43.875921], [-79.232566, 43.868316], [-79.228804, 43.865879], [-79.227586, 43.86825], [-79.224816, 43.869773], [-79.221362, 43.870486], [-79.215883, 43.869552], [-79.212178, 43.868989], [-79.215984, 43.862601], [-79.223979, 43.861102], [-79.224746, 43.86225], [-79.227079, 43.864747], [-79.232257, 43.863842], [-79.232877, 43.864886], [-79.235645, 43.86577], [-79.240551, 43.865822], [-79.242494, 43.865525], [-79.242055, 43.863553], [-79.2401, 43.861056], [-79.235145, 43.861654], [-79.233822, 43.860387], [-79.232184, 43.859921], [-79.23722, 43.857921], [-79.238215, 43.855653], [-79.240491, 43.855191], [-79.243854, 43.856569], [-79.244391, 43.857888], [-79.246777, 43.858916], [-79.249965, 43.858667], [-79.250189, 43.856946], [-79.25245, 43.85628], [-79.255417, 43.856361], [-79.258522, 43.854444], [-79.262234, 43.853479], [-79.267421, 43.852238], [-79.271502, 43.851311], [-79.275633, 43.850338], [-79.27932, 43.849447], [-79.284376, 43.848284], [-79.286767, 43.847702], [-79.290136, 43.846925], [-79.294241, 43.845976], [-79.298558, 43.844984], [-79.30454, 43.843691], [-79.305968, 43.843384], [-79.310594, 43.842347], [-79.313276, 43.841627], [-79.316692, 43.840819], [-79.320125, 43.839981], [-79.324654, 43.838886], [-79.328837, 43.837916], [-79.331952, 43.836686], [-79.335334, 43.832775], [-79.337858, 43.830699], [-79.339843, 43.829145], [-79.34029, 43.827477], [-79.338844, 43.826468], [-79.341402, 43.824133], [-79.344769, 43.823349], [-79.347202, 43.822766], [-79.350357, 43.822295]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_dbb9f169a34c38d84b87823565991f27.bindTooltip(
                `<div>
                     14 14TH AVENUE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_dbb9f169a34c38d84b87823565991f27.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_3e19005ddf0efeaf8e895cfa7dd7e4eb_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#4B6CB4", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_3e19005ddf0efeaf8e895cfa7dd7e4eb_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_3e19005ddf0efeaf8e895cfa7dd7e4eb = L.geoJson(null, {
                onEachFeature: geo_json_3e19005ddf0efeaf8e895cfa7dd7e4eb_onEachFeature,
            
                style: geo_json_3e19005ddf0efeaf8e895cfa7dd7e4eb_styler,
            ...{
}
        });

        function geo_json_3e19005ddf0efeaf8e895cfa7dd7e4eb_add (data) {
            geo_json_3e19005ddf0efeaf8e895cfa7dd7e4eb
                .addData(data);
        }
            geo_json_3e19005ddf0efeaf8e895cfa7dd7e4eb_add({"features": [{"geometry": {"coordinates": [[-79.462336, 43.848124], [-79.459176, 43.847478], [-79.453336, 43.848699], [-79.448581, 43.849655], [-79.445704, 43.850264], [-79.440159, 43.851441], [-79.435673, 43.852371], [-79.433448, 43.852814], [-79.431741, 43.853213], [-79.425889, 43.85461], [-79.423976, 43.854918], [-79.421689, 43.855354], [-79.416426, 43.856521], [-79.411293, 43.857634], [-79.403154, 43.858649], [-79.396414, 43.860144], [-79.389549, 43.861649], [-79.387236, 43.862243], [-79.384401, 43.862976], [-79.382088, 43.863469], [-79.37022, 43.866355], [-79.363112, 43.86772], [-79.35751, 43.868847], [-79.352826, 43.869915], [-79.348308, 43.870963], [-79.343303, 43.872084], [-79.339006, 43.873763], [-79.332325, 43.875314], [-79.32702, 43.876502], [-79.321988, 43.877689], [-79.317446, 43.878739], [-79.314497, 43.879274], [-79.310845, 43.880106], [-79.304424, 43.881573], [-79.299615, 43.882677], [-79.293919, 43.883978], [-79.289249, 43.885051], [-79.285011, 43.886419], [-79.280474, 43.887445], [-79.273825, 43.888994], [-79.268945, 43.890163], [-79.264393, 43.891833], [-79.258838, 43.893121], [-79.255532, 43.893891], [-79.250827, 43.894936], [-79.246525, 43.896029], [-79.243039, 43.896828], [-79.239886, 43.897507], [-79.238995, 43.894803], [-79.238255, 43.891857], [-79.237438, 43.888719], [-79.237123, 43.887206], [-79.236317, 43.884493], [-79.231417, 43.880368]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_3e19005ddf0efeaf8e895cfa7dd7e4eb.bindTooltip(
                `<div>
                     16 16TH AVENUE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_3e19005ddf0efeaf8e895cfa7dd7e4eb.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_6286f7bbc8c38c1b1963eca075bb0d8f_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#4B6CB4", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_6286f7bbc8c38c1b1963eca075bb0d8f_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_6286f7bbc8c38c1b1963eca075bb0d8f = L.geoJson(null, {
                onEachFeature: geo_json_6286f7bbc8c38c1b1963eca075bb0d8f_onEachFeature,
            
                style: geo_json_6286f7bbc8c38c1b1963eca075bb0d8f_styler,
            ...{
}
        });

        function geo_json_6286f7bbc8c38c1b1963eca075bb0d8f_add (data) {
            geo_json_6286f7bbc8c38c1b1963eca075bb0d8f
                .addData(data);
        }
            geo_json_6286f7bbc8c38c1b1963eca075bb0d8f_add({"features": [{"geometry": {"coordinates": [[-79.363112, 43.86772], [-79.35751, 43.868847], [-79.352826, 43.869915], [-79.348308, 43.870963], [-79.343303, 43.872084], [-79.339006, 43.873763], [-79.332325, 43.875314], [-79.32702, 43.876502], [-79.321988, 43.877689], [-79.317446, 43.878739], [-79.314497, 43.879274], [-79.310845, 43.880106], [-79.304424, 43.881573], [-79.299615, 43.882677], [-79.293919, 43.883978], [-79.289249, 43.885051], [-79.285011, 43.886419], [-79.280474, 43.887445], [-79.273825, 43.888994], [-79.268945, 43.890163], [-79.264393, 43.891833], [-79.258838, 43.893121], [-79.255532, 43.893891], [-79.250827, 43.894936], [-79.246525, 43.896029], [-79.243039, 43.896828], [-79.239886, 43.897507], [-79.238995, 43.894803], [-79.238255, 43.891857], [-79.237438, 43.888719], [-79.237123, 43.887206], [-79.236317, 43.884493], [-79.231417, 43.880368]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_6286f7bbc8c38c1b1963eca075bb0d8f.bindTooltip(
                `<div>
                     16 16TH AVENUE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_6286f7bbc8c38c1b1963eca075bb0d8f.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_a12154c5c04dceeb842960d18bf26602_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#4B6CB4", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_a12154c5c04dceeb842960d18bf26602_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_a12154c5c04dceeb842960d18bf26602 = L.geoJson(null, {
                onEachFeature: geo_json_a12154c5c04dceeb842960d18bf26602_onEachFeature,
            
                style: geo_json_a12154c5c04dceeb842960d18bf26602_styler,
            ...{
}
        });

        function geo_json_a12154c5c04dceeb842960d18bf26602_add (data) {
            geo_json_a12154c5c04dceeb842960d18bf26602
                .addData(data);
        }
            geo_json_a12154c5c04dceeb842960d18bf26602_add({"features": [{"geometry": {"coordinates": [[-79.231417, 43.880368], [-79.235156, 43.880494], [-79.235961, 43.883962], [-79.23433, 43.884453], [-79.229955, 43.885504], [-79.229499, 43.886931], [-79.229819, 43.888092], [-79.230233, 43.889539], [-79.23086, 43.892056], [-79.23142, 43.894171], [-79.231086, 43.895559], [-79.231563, 43.897382], [-79.231663, 43.898272], [-79.234841, 43.899132], [-79.240507, 43.8976], [-79.242724, 43.897133], [-79.245758, 43.89642], [-79.250078, 43.89538], [-79.255162, 43.894187], [-79.258402, 43.893399], [-79.263777, 43.892147], [-79.273328, 43.889366], [-79.279855, 43.887836], [-79.284591, 43.886748], [-79.28854, 43.885446], [-79.293463, 43.884331], [-79.299055, 43.88305], [-79.303697, 43.881926], [-79.310168, 43.880445], [-79.313892, 43.879645], [-79.31704, 43.879032], [-79.321309, 43.878027], [-79.326604, 43.876847], [-79.331888, 43.875608], [-79.338317, 43.874148], [-79.342901, 43.87241], [-79.347823, 43.871292], [-79.352193, 43.870281], [-79.357024, 43.869215], [-79.362423, 43.868078], [-79.369575, 43.866711], [-79.381507, 43.86391], [-79.386546, 43.862673], [-79.390447, 43.86172], [-79.395588, 43.860576], [-79.40249, 43.859024], [-79.410677, 43.858001], [-79.416038, 43.856802], [-79.421105, 43.855699], [-79.423587, 43.855157], [-79.425478, 43.854879], [-79.43261, 43.85327], [-79.43634, 43.852438], [-79.439784, 43.851728], [-79.445248, 43.850635], [-79.448837, 43.849832], [-79.453123, 43.848964], [-79.455343, 43.8485], [-79.458275, 43.84789], [-79.459409, 43.851565], [-79.462001, 43.854702], [-79.464239, 43.85433], [-79.463649, 43.85164], [-79.463049, 43.84998], [-79.462336, 43.848124]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_a12154c5c04dceeb842960d18bf26602.bindTooltip(
                `<div>
                     16 16TH AVENUE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_a12154c5c04dceeb842960d18bf26602.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_57e00bedc41e5bd939771313e7d56a38_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#4B6CB4", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_57e00bedc41e5bd939771313e7d56a38_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_57e00bedc41e5bd939771313e7d56a38 = L.geoJson(null, {
                onEachFeature: geo_json_57e00bedc41e5bd939771313e7d56a38_onEachFeature,
            
                style: geo_json_57e00bedc41e5bd939771313e7d56a38_styler,
            ...{
}
        });

        function geo_json_57e00bedc41e5bd939771313e7d56a38_add (data) {
            geo_json_57e00bedc41e5bd939771313e7d56a38
                .addData(data);
        }
            geo_json_57e00bedc41e5bd939771313e7d56a38_add({"features": [{"geometry": {"coordinates": [[-79.362423, 43.868078], [-79.369575, 43.866711], [-79.381507, 43.86391], [-79.386546, 43.862673], [-79.390447, 43.86172], [-79.395588, 43.860576], [-79.40249, 43.859024], [-79.410677, 43.858001], [-79.416038, 43.856802], [-79.421105, 43.855699], [-79.423587, 43.855157], [-79.425478, 43.854879], [-79.43261, 43.85327], [-79.43634, 43.852438], [-79.439784, 43.851728], [-79.445248, 43.850635], [-79.448837, 43.849832], [-79.453123, 43.848964], [-79.455343, 43.8485], [-79.458275, 43.84789], [-79.459409, 43.851565], [-79.462001, 43.854702], [-79.464239, 43.85433], [-79.463649, 43.85164], [-79.463049, 43.84998], [-79.462336, 43.848124]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_57e00bedc41e5bd939771313e7d56a38.bindTooltip(
                `<div>
                     16 16TH AVENUE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_57e00bedc41e5bd939771313e7d56a38.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_29e2e4e6f9984990988ca617052ede75_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#6DC069", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_29e2e4e6f9984990988ca617052ede75_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_29e2e4e6f9984990988ca617052ede75 = L.geoJson(null, {
                onEachFeature: geo_json_29e2e4e6f9984990988ca617052ede75_onEachFeature,
            
                style: geo_json_29e2e4e6f9984990988ca617052ede75_styler,
            ...{
}
        });

        function geo_json_29e2e4e6f9984990988ca617052ede75_add (data) {
            geo_json_29e2e4e6f9984990988ca617052ede75
                .addData(data);
        }
            geo_json_29e2e4e6f9984990988ca617052ede75_add({"features": [{"geometry": {"coordinates": [[-79.337417, 43.894645], [-79.333628, 43.893159], [-79.333657, 43.890592], [-79.334171, 43.889137], [-79.333403, 43.887061], [-79.32831, 43.888487], [-79.323107, 43.89035], [-79.319968, 43.890723], [-79.317573, 43.890999], [-79.315666, 43.888557], [-79.312012, 43.889341], [-79.310452, 43.889737], [-79.307854, 43.890502], [-79.305836, 43.891548], [-79.303303, 43.892845], [-79.301346, 43.89335], [-79.298708, 43.893879], [-79.296969, 43.89412], [-79.29339, 43.894361], [-79.29145, 43.894616], [-79.287758, 43.895793], [-79.283614, 43.896732], [-79.279211, 43.897649], [-79.275559, 43.898488], [-79.271909, 43.899184], [-79.269391, 43.89966], [-79.266418, 43.90004], [-79.263672, 43.900691], [-79.259173, 43.901802], [-79.255776, 43.902379], [-79.254047, 43.902596], [-79.249557, 43.902322], [-79.247642, 43.902198], [-79.244123, 43.902358], [-79.240989, 43.902247], [-79.239467, 43.902324], [-79.236009, 43.902684], [-79.232889, 43.902285], [-79.23155, 43.901479], [-79.231446, 43.899209], [-79.231798, 43.897471], [-79.231421, 43.895888], [-79.231637, 43.894166], [-79.231023, 43.891722], [-79.230522, 43.889773], [-79.230045, 43.888273], [-79.229593, 43.886669], [-79.229334, 43.885818], [-79.229063, 43.884952], [-79.226104, 43.881117], [-79.231488, 43.880689]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_29e2e4e6f9984990988ca617052ede75.bindTooltip(
                `<div>
                     18 BUR OAK
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_29e2e4e6f9984990988ca617052ede75.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_720a356153828e7f45c23879c288a94f_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#6DC069", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_720a356153828e7f45c23879c288a94f_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_720a356153828e7f45c23879c288a94f = L.geoJson(null, {
                onEachFeature: geo_json_720a356153828e7f45c23879c288a94f_onEachFeature,
            
                style: geo_json_720a356153828e7f45c23879c288a94f_styler,
            ...{
}
        });

        function geo_json_720a356153828e7f45c23879c288a94f_add (data) {
            geo_json_720a356153828e7f45c23879c288a94f
                .addData(data);
        }
            geo_json_720a356153828e7f45c23879c288a94f_add({"features": [{"geometry": {"coordinates": [[-79.231488, 43.880689], [-79.229019, 43.878971], [-79.225589, 43.880425], [-79.227727, 43.884372], [-79.229499, 43.886931], [-79.229819, 43.888092], [-79.230233, 43.889539], [-79.23086, 43.892056], [-79.23142, 43.894171], [-79.231086, 43.895559], [-79.231563, 43.897382], [-79.231663, 43.898272], [-79.231188, 43.901271], [-79.233463, 43.90254], [-79.235598, 43.902758], [-79.240356, 43.90244], [-79.241849, 43.902395], [-79.243703, 43.90246], [-79.247233, 43.902364], [-79.249689, 43.90247], [-79.253663, 43.902711], [-79.255492, 43.902497], [-79.258745, 43.902013], [-79.263993, 43.900783], [-79.265616, 43.900394], [-79.269085, 43.899854], [-79.271666, 43.899361], [-79.27512, 43.89872], [-79.275835, 43.898527], [-79.280051, 43.897616], [-79.28314, 43.89694], [-79.287415, 43.896036], [-79.290704, 43.894899], [-79.293171, 43.89455], [-79.296676, 43.894326], [-79.300991, 43.89355], [-79.303523, 43.892942], [-79.30507, 43.892145], [-79.305603, 43.89183], [-79.307722, 43.890708], [-79.309378, 43.890154], [-79.311703, 43.889605], [-79.313366, 43.889234], [-79.316297, 43.888608], [-79.318514, 43.890971], [-79.322977, 43.890421], [-79.328127, 43.889539], [-79.333408, 43.887154], [-79.333999, 43.889157], [-79.333511, 43.890436], [-79.333521, 43.893029], [-79.336632, 43.893695], [-79.337417, 43.894645]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_720a356153828e7f45c23879c288a94f.bindTooltip(
                `<div>
                     18 BUR OAK
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_720a356153828e7f45c23879c288a94f.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_f67dfc59a1c0a7372cb6af5d515b9f1d_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#806A50", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_f67dfc59a1c0a7372cb6af5d515b9f1d_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_f67dfc59a1c0a7372cb6af5d515b9f1d = L.geoJson(null, {
                onEachFeature: geo_json_f67dfc59a1c0a7372cb6af5d515b9f1d_onEachFeature,
            
                style: geo_json_f67dfc59a1c0a7372cb6af5d515b9f1d_styler,
            ...{
}
        });

        function geo_json_f67dfc59a1c0a7372cb6af5d515b9f1d_add (data) {
            geo_json_f67dfc59a1c0a7372cb6af5d515b9f1d
                .addData(data);
        }
            geo_json_f67dfc59a1c0a7372cb6af5d515b9f1d_add({"features": [{"geometry": {"coordinates": [[-79.512468, 43.778709], [-79.516748, 43.776552], [-79.521541, 43.776279], [-79.520604, 43.778298], [-79.520995, 43.78073], [-79.523393, 43.782688], [-79.523822, 43.789186], [-79.523808, 43.791666], [-79.524243, 43.793929], [-79.527912, 43.796935], [-79.526392, 43.803755], [-79.526946, 43.806206], [-79.52756, 43.809123], [-79.528131, 43.812248], [-79.528834, 43.815035], [-79.529804, 43.819467], [-79.530738, 43.82349], [-79.53379, 43.827129], [-79.532409, 43.830627], [-79.53296, 43.83299], [-79.53354, 43.83565], [-79.534052, 43.838208], [-79.535011, 43.842577], [-79.535722, 43.845875], [-79.540422, 43.847951], [-79.536794, 43.851009], [-79.537308, 43.853307], [-79.538119, 43.856894], [-79.53929, 43.862294], [-79.540001, 43.864936], [-79.542708, 43.865468], [-79.544946, 43.865298], [-79.545384, 43.866527]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_f67dfc59a1c0a7372cb6af5d515b9f1d.bindTooltip(
                `<div>
                     20 JANE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_f67dfc59a1c0a7372cb6af5d515b9f1d.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_2909e3803f352d70a372a9e6cde086e5_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#806A50", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_2909e3803f352d70a372a9e6cde086e5_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_2909e3803f352d70a372a9e6cde086e5 = L.geoJson(null, {
                onEachFeature: geo_json_2909e3803f352d70a372a9e6cde086e5_onEachFeature,
            
                style: geo_json_2909e3803f352d70a372a9e6cde086e5_styler,
            ...{
}
        });

        function geo_json_2909e3803f352d70a372a9e6cde086e5_add (data) {
            geo_json_2909e3803f352d70a372a9e6cde086e5
                .addData(data);
        }
            geo_json_2909e3803f352d70a372a9e6cde086e5_add({"features": [{"geometry": {"coordinates": [[-79.53379, 43.827129], [-79.532409, 43.830627], [-79.53296, 43.83299], [-79.53354, 43.83565], [-79.534052, 43.838208], [-79.535011, 43.842577], [-79.535722, 43.845875], [-79.540422, 43.847951], [-79.536794, 43.851009], [-79.537308, 43.853307], [-79.538119, 43.856894], [-79.53929, 43.862294], [-79.540001, 43.864936], [-79.542708, 43.865468], [-79.544946, 43.865298], [-79.545384, 43.866527]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_2909e3803f352d70a372a9e6cde086e5.bindTooltip(
                `<div>
                     20 JANE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_2909e3803f352d70a372a9e6cde086e5.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_992d96c1583d69cb591d29262e691f60_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#806A50", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_992d96c1583d69cb591d29262e691f60_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_992d96c1583d69cb591d29262e691f60 = L.geoJson(null, {
                onEachFeature: geo_json_992d96c1583d69cb591d29262e691f60_onEachFeature,
            
                style: geo_json_992d96c1583d69cb591d29262e691f60_styler,
            ...{
}
        });

        function geo_json_992d96c1583d69cb591d29262e691f60_add (data) {
            geo_json_992d96c1583d69cb591d29262e691f60
                .addData(data);
        }
            geo_json_992d96c1583d69cb591d29262e691f60_add({"features": [{"geometry": {"coordinates": [[-79.545384, 43.866527], [-79.541318, 43.868286], [-79.540466, 43.8661], [-79.539765, 43.862852], [-79.538538, 43.857304], [-79.537758, 43.853789], [-79.537265, 43.851654], [-79.536896, 43.849698], [-79.540468, 43.847476], [-79.536968, 43.84925], [-79.535935, 43.845353], [-79.53543, 43.843215], [-79.5345, 43.838684], [-79.534274, 43.837784], [-79.534, 43.836302], [-79.533411, 43.833197], [-79.532934, 43.831187], [-79.53213, 43.827908], [-79.533979, 43.827344], [-79.53123, 43.824221], [-79.530248, 43.819958], [-79.529235, 43.815488], [-79.528471, 43.811871], [-79.527951, 43.809614], [-79.527274, 43.806477], [-79.526681, 43.803413], [-79.525603, 43.798647], [-79.528383, 43.796736], [-79.524755, 43.794343], [-79.524065, 43.791462], [-79.524063, 43.789759], [-79.523259, 43.782744], [-79.521298, 43.780723], [-79.520924, 43.775533], [-79.516435, 43.77638], [-79.512468, 43.778709]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_992d96c1583d69cb591d29262e691f60.bindTooltip(
                `<div>
                     20 JANE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_992d96c1583d69cb591d29262e691f60.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_d2811d6ab5983e385ab3186aee7163af_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00838B", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_d2811d6ab5983e385ab3186aee7163af_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_d2811d6ab5983e385ab3186aee7163af = L.geoJson(null, {
                onEachFeature: geo_json_d2811d6ab5983e385ab3186aee7163af_onEachFeature,
            
                style: geo_json_d2811d6ab5983e385ab3186aee7163af_styler,
            ...{
}
        });

        function geo_json_d2811d6ab5983e385ab3186aee7163af_add (data) {
            geo_json_d2811d6ab5983e385ab3186aee7163af
                .addData(data);
        }
            geo_json_d2811d6ab5983e385ab3186aee7163af_add({"features": [{"geometry": {"coordinates": [[-79.534583, 43.827081], [-79.542212, 43.828887], [-79.55202, 43.826906], [-79.555823, 43.826346], [-79.556448, 43.82777], [-79.55702, 43.830162], [-79.560575, 43.834026], [-79.564287, 43.833769], [-79.566769, 43.833744], [-79.56932, 43.83383], [-79.569468, 43.83722], [-79.570178, 43.83901], [-79.571112, 43.841492], [-79.571399, 43.842485], [-79.5722, 43.84433], [-79.5738, 43.846706], [-79.574717, 43.848], [-79.575455, 43.849911], [-79.57611, 43.85128], [-79.574035, 43.851958], [-79.571482, 43.852527], [-79.566892, 43.853979], [-79.563308, 43.855378], [-79.559878, 43.856037], [-79.55611, 43.857198], [-79.554162, 43.857712], [-79.553533, 43.855461], [-79.55324, 43.854185], [-79.552564, 43.850379], [-79.554045, 43.848165], [-79.554392, 43.846448], [-79.553412, 43.843693], [-79.552213, 43.841823], [-79.551432, 43.839619], [-79.550958, 43.837511], [-79.550911, 43.835907], [-79.554735, 43.835093], [-79.557307, 43.834626], [-79.558264, 43.833762], [-79.557495, 43.830644], [-79.556892, 43.828175], [-79.5554, 43.826123], [-79.551817, 43.826688], [-79.539777, 43.829052], [-79.534583, 43.827081]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_d2811d6ab5983e385ab3186aee7163af.bindTooltip(
                `<div>
                     21 VELLORE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_d2811d6ab5983e385ab3186aee7163af.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_a1227afbf517fea6c8aa9da952e8a35e_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#F58220", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_a1227afbf517fea6c8aa9da952e8a35e_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_a1227afbf517fea6c8aa9da952e8a35e = L.geoJson(null, {
                onEachFeature: geo_json_a1227afbf517fea6c8aa9da952e8a35e_onEachFeature,
            
                style: geo_json_a1227afbf517fea6c8aa9da952e8a35e_styler,
            ...{
}
        });

        function geo_json_a1227afbf517fea6c8aa9da952e8a35e_add (data) {
            geo_json_a1227afbf517fea6c8aa9da952e8a35e
                .addData(data);
        }
            geo_json_a1227afbf517fea6c8aa9da952e8a35e_add({"features": [{"geometry": {"coordinates": [[-79.414632, 43.782515], [-79.416698, 43.78496], [-79.417335, 43.787532], [-79.417977, 43.790138], [-79.418316, 43.79149], [-79.418994, 43.794272], [-79.42067, 43.79802], [-79.424712, 43.797159], [-79.429061, 43.796213], [-79.42968, 43.798744], [-79.433509, 43.802465], [-79.435376, 43.803713], [-79.437772, 43.805606], [-79.440512, 43.805047], [-79.441468, 43.806647], [-79.442859, 43.810774], [-79.444047, 43.812237], [-79.449522, 43.811062], [-79.454388, 43.809634], [-79.45019, 43.81265], [-79.450745, 43.814571], [-79.451357, 43.81695], [-79.452742, 43.822771], [-79.465218, 43.827051], [-79.467594, 43.826541], [-79.470806, 43.825866], [-79.473164, 43.82612], [-79.473557, 43.827517], [-79.473946, 43.829446], [-79.46984, 43.830216], [-79.466259, 43.831467], [-79.467509, 43.834475], [-79.468063, 43.835623], [-79.468636, 43.837566], [-79.469417, 43.84118], [-79.469243, 43.842754], [-79.469879, 43.84467], [-79.470464, 43.84618], [-79.469225, 43.848925], [-79.46989, 43.85283], [-79.467467, 43.853492], [-79.465819, 43.857284], [-79.46595, 43.860607], [-79.468268, 43.864625], [-79.470943, 43.872704], [-79.471879, 43.874742], [-79.474439, 43.875903], [-79.478994, 43.87698], [-79.482479, 43.875567], [-79.484685, 43.877361], [-79.485946, 43.879945], [-79.481903, 43.880988]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_a1227afbf517fea6c8aa9da952e8a35e.bindTooltip(
                `<div>
                     23 THORNHILL WOODS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_a1227afbf517fea6c8aa9da952e8a35e.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_c1c82cae53cc20abd82a9f21dea86a41_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#F58220", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_c1c82cae53cc20abd82a9f21dea86a41_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_c1c82cae53cc20abd82a9f21dea86a41 = L.geoJson(null, {
                onEachFeature: geo_json_c1c82cae53cc20abd82a9f21dea86a41_onEachFeature,
            
                style: geo_json_c1c82cae53cc20abd82a9f21dea86a41_styler,
            ...{
}
        });

        function geo_json_c1c82cae53cc20abd82a9f21dea86a41_add (data) {
            geo_json_c1c82cae53cc20abd82a9f21dea86a41
                .addData(data);
        }
            geo_json_c1c82cae53cc20abd82a9f21dea86a41_add({"features": [{"geometry": {"coordinates": [[-79.454388, 43.809634], [-79.45019, 43.81265], [-79.450745, 43.814571], [-79.451357, 43.81695], [-79.452742, 43.822771], [-79.465218, 43.827051], [-79.467594, 43.826541], [-79.470806, 43.825866], [-79.473164, 43.82612], [-79.473557, 43.827517], [-79.473946, 43.829446], [-79.46984, 43.830216], [-79.466259, 43.831467], [-79.467509, 43.834475], [-79.468063, 43.835623], [-79.468636, 43.837566], [-79.469417, 43.84118], [-79.469243, 43.842754], [-79.469879, 43.84467], [-79.470464, 43.84618], [-79.469225, 43.848925], [-79.46989, 43.85283], [-79.467467, 43.853492], [-79.465819, 43.857284], [-79.46595, 43.860607], [-79.468268, 43.864625], [-79.470943, 43.872704], [-79.471879, 43.874742], [-79.474439, 43.875903], [-79.478994, 43.87698], [-79.482479, 43.875567], [-79.484685, 43.877361], [-79.485946, 43.879945], [-79.481903, 43.880988]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_c1c82cae53cc20abd82a9f21dea86a41.bindTooltip(
                `<div>
                     23 THORNHILL WOODS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_c1c82cae53cc20abd82a9f21dea86a41.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_122ea09cd4c719b04968e9d58294c8d4_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#F58220", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_122ea09cd4c719b04968e9d58294c8d4_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_122ea09cd4c719b04968e9d58294c8d4 = L.geoJson(null, {
                onEachFeature: geo_json_122ea09cd4c719b04968e9d58294c8d4_onEachFeature,
            
                style: geo_json_122ea09cd4c719b04968e9d58294c8d4_styler,
            ...{
}
        });

        function geo_json_122ea09cd4c719b04968e9d58294c8d4_add (data) {
            geo_json_122ea09cd4c719b04968e9d58294c8d4
                .addData(data);
        }
            geo_json_122ea09cd4c719b04968e9d58294c8d4_add({"features": [{"geometry": {"coordinates": [[-79.481903, 43.880988], [-79.481466, 43.880467], [-79.48102, 43.879229], [-79.479559, 43.877269], [-79.475616, 43.876017], [-79.472591, 43.875122], [-79.471082, 43.872537], [-79.468365, 43.863982], [-79.46635, 43.861192], [-79.465885, 43.857078], [-79.465192, 43.854076], [-79.469861, 43.853103], [-79.469605, 43.849295], [-79.47039, 43.845481], [-79.46978, 43.84389], [-79.469368, 43.84257], [-79.469577, 43.840649], [-79.468849, 43.837858], [-79.468315, 43.835945], [-79.467787, 43.834668], [-79.466403, 43.831436], [-79.468736, 43.830567], [-79.473707, 43.829957], [-79.47387, 43.828122], [-79.472772, 43.825685], [-79.471335, 43.825641], [-79.468038, 43.826334], [-79.464866, 43.827005], [-79.453091, 43.822544], [-79.452505, 43.820475], [-79.45187, 43.817555], [-79.451233, 43.814913], [-79.450243, 43.811349], [-79.453891, 43.809631], [-79.45023, 43.810619], [-79.443685, 43.812106], [-79.443126, 43.811129], [-79.44251, 43.808763], [-79.441628, 43.806406], [-79.440044, 43.804899], [-79.437017, 43.805531], [-79.435975, 43.803963], [-79.434099, 43.802664], [-79.42995, 43.798965], [-79.429603, 43.796617], [-79.426559, 43.796526], [-79.422779, 43.797323], [-79.420037, 43.797434], [-79.419718, 43.796088], [-79.419191, 43.793992], [-79.418625, 43.791289], [-79.418069, 43.789452], [-79.417496, 43.7872], [-79.414632, 43.782515]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_122ea09cd4c719b04968e9d58294c8d4.bindTooltip(
                `<div>
                     23 THORNHILL WOODS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_122ea09cd4c719b04968e9d58294c8d4.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_29194befe69838e511524e92d3ca6f03_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00AEEF", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_29194befe69838e511524e92d3ca6f03_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_29194befe69838e511524e92d3ca6f03 = L.geoJson(null, {
                onEachFeature: geo_json_29194befe69838e511524e92d3ca6f03_onEachFeature,
            
                style: geo_json_29194befe69838e511524e92d3ca6f03_styler,
            ...{
}
        });

        function geo_json_29194befe69838e511524e92d3ca6f03_add (data) {
            geo_json_29194befe69838e511524e92d3ca6f03
                .addData(data);
        }
            geo_json_29194befe69838e511524e92d3ca6f03_add({"features": [{"geometry": {"coordinates": [[-79.346338, 43.775808], [-79.342943, 43.775868], [-79.335479, 43.775481], [-79.330541, 43.774949], [-79.32708, 43.774577], [-79.324141, 43.778067], [-79.325214, 43.780213], [-79.326271, 43.782417], [-79.32721, 43.784493], [-79.327918, 43.785976], [-79.329384, 43.789098], [-79.330595, 43.791619], [-79.331074, 43.792839], [-79.332558, 43.795926], [-79.333396, 43.797923], [-79.334544, 43.800381], [-79.336078, 43.803901], [-79.337021, 43.805979], [-79.338118, 43.808407], [-79.338907, 43.810277], [-79.339966, 43.813025], [-79.341003, 43.815216], [-79.341823, 43.816952], [-79.342479, 43.818425], [-79.343213, 43.819458], [-79.344535, 43.820974], [-79.347202, 43.822766], [-79.350357, 43.822295], [-79.351427, 43.825126], [-79.352756, 43.830119], [-79.353133, 43.831433], [-79.354166, 43.835338], [-79.354714, 43.837472], [-79.356215, 43.843412], [-79.356842, 43.845656], [-79.357702, 43.849333], [-79.358911, 43.853826], [-79.359677, 43.856597], [-79.360414, 43.859277], [-79.361656, 43.864216], [-79.362576, 43.867763], [-79.363442, 43.871385], [-79.364502, 43.875561], [-79.364737, 43.876569], [-79.365843, 43.880997], [-79.366999, 43.885748], [-79.362196, 43.888581], [-79.363709, 43.890459], [-79.365412, 43.892558], [-79.365922, 43.89377], [-79.367608, 43.896948], [-79.36953, 43.896778], [-79.371269, 43.896769], [-79.372906, 43.896763], [-79.376758, 43.896583], [-79.378487, 43.896996], [-79.377247, 43.899746], [-79.377272, 43.901278], [-79.378938, 43.905326], [-79.379778, 43.907319], [-79.378651, 43.910622], [-79.379852, 43.912534], [-79.381294, 43.914909]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_29194befe69838e511524e92d3ca6f03.bindTooltip(
                `<div>
                     24 WOODBINE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_29194befe69838e511524e92d3ca6f03.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_df0c8e772ffc4648a6760667d19193a3_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00AEEF", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_df0c8e772ffc4648a6760667d19193a3_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_df0c8e772ffc4648a6760667d19193a3 = L.geoJson(null, {
                onEachFeature: geo_json_df0c8e772ffc4648a6760667d19193a3_onEachFeature,
            
                style: geo_json_df0c8e772ffc4648a6760667d19193a3_styler,
            ...{
}
        });

        function geo_json_df0c8e772ffc4648a6760667d19193a3_add (data) {
            geo_json_df0c8e772ffc4648a6760667d19193a3
                .addData(data);
        }
            geo_json_df0c8e772ffc4648a6760667d19193a3_add({"features": [{"geometry": {"coordinates": [[-79.381294, 43.914909], [-79.380689, 43.912733], [-79.378322, 43.910176], [-79.379528, 43.905808], [-79.378258, 43.903001], [-79.377072, 43.896518], [-79.373312, 43.896581], [-79.370377, 43.896575], [-79.367871, 43.896972], [-79.366251, 43.894185], [-79.36526, 43.89187], [-79.362932, 43.889548], [-79.361844, 43.887451], [-79.366976, 43.884408], [-79.366257, 43.881318], [-79.365167, 43.876989], [-79.363903, 43.871785], [-79.362975, 43.868053], [-79.362024, 43.864442], [-79.3608, 43.85964], [-79.360139, 43.857021], [-79.359333, 43.854144], [-79.358174, 43.850028], [-79.357292, 43.846146], [-79.355165, 43.837844], [-79.354639, 43.835853], [-79.353594, 43.831869], [-79.35323, 43.830486], [-79.35187, 43.825433], [-79.349745, 43.822193], [-79.346159, 43.822833], [-79.344993, 43.821359], [-79.342749, 43.818571], [-79.341562, 43.815915], [-79.340676, 43.813805], [-79.339372, 43.810755], [-79.338487, 43.80862], [-79.337564, 43.806541], [-79.336629, 43.804311], [-79.334866, 43.800537], [-79.333852, 43.798156], [-79.332894, 43.79609], [-79.331717, 43.79332], [-79.330971, 43.791868], [-79.329791, 43.789359], [-79.328096, 43.785808], [-79.327232, 43.783965], [-79.326542, 43.782507], [-79.32558, 43.780483], [-79.32436, 43.777828], [-79.323302, 43.775518], [-79.326413, 43.774797], [-79.331695, 43.775292], [-79.335693, 43.775748], [-79.34506, 43.775683]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_df0c8e772ffc4648a6760667d19193a3.bindTooltip(
                `<div>
                     24 WOODBINE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_df0c8e772ffc4648a6760667d19193a3.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_4384e376bf30ca14f5795077ff406f79_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00AEEF", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_4384e376bf30ca14f5795077ff406f79_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_4384e376bf30ca14f5795077ff406f79 = L.geoJson(null, {
                onEachFeature: geo_json_4384e376bf30ca14f5795077ff406f79_onEachFeature,
            
                style: geo_json_4384e376bf30ca14f5795077ff406f79_styler,
            ...{
}
        });

        function geo_json_4384e376bf30ca14f5795077ff406f79_add (data) {
            geo_json_4384e376bf30ca14f5795077ff406f79
                .addData(data);
        }
            geo_json_4384e376bf30ca14f5795077ff406f79_add({"features": [{"geometry": {"coordinates": [[-79.346338, 43.775808], [-79.342943, 43.775868], [-79.335479, 43.775481], [-79.330541, 43.774949], [-79.32708, 43.774577], [-79.324141, 43.778067], [-79.325214, 43.780213], [-79.326271, 43.782417], [-79.32721, 43.784493], [-79.327918, 43.785976], [-79.329384, 43.789098], [-79.330595, 43.791619], [-79.331074, 43.792839], [-79.332558, 43.795926], [-79.333396, 43.797923], [-79.334544, 43.800381], [-79.336078, 43.803901], [-79.337021, 43.805979], [-79.338118, 43.808407], [-79.338907, 43.810277], [-79.339966, 43.813025], [-79.341003, 43.815216], [-79.341823, 43.816952], [-79.342479, 43.818425], [-79.343213, 43.819458], [-79.344535, 43.820974], [-79.347202, 43.822766], [-79.350357, 43.822295], [-79.351427, 43.825126], [-79.352756, 43.830119], [-79.353133, 43.831433], [-79.354166, 43.835338], [-79.354714, 43.837472], [-79.356215, 43.843412], [-79.357935, 43.845783], [-79.360337, 43.843493], [-79.362132, 43.843235], [-79.365022, 43.843518], [-79.366134, 43.844796], [-79.363746, 43.84638], [-79.360976, 43.847329], [-79.361105, 43.84881], [-79.361439, 43.849634], [-79.361944, 43.851153], [-79.36371, 43.852416], [-79.366642, 43.851761], [-79.36776, 43.853717], [-79.365364, 43.854408], [-79.363704, 43.854787], [-79.362015, 43.855908], [-79.362492, 43.858671], [-79.36144, 43.859232], [-79.361656, 43.864216], [-79.362576, 43.867763], [-79.363442, 43.871385], [-79.364502, 43.875561], [-79.368041, 43.876536], [-79.371399, 43.876124], [-79.374667, 43.875692], [-79.376019, 43.879652], [-79.373417, 43.880705], [-79.37246, 43.88218], [-79.372981, 43.884523], [-79.370487, 43.885128], [-79.36778, 43.88568], [-79.362196, 43.888581], [-79.363709, 43.890459], [-79.365412, 43.892558], [-79.365922, 43.89377], [-79.367608, 43.896948], [-79.36953, 43.896778], [-79.371269, 43.896769], [-79.372906, 43.896763], [-79.376758, 43.896583], [-79.378487, 43.896996], [-79.377247, 43.899746], [-79.377272, 43.901278], [-79.378938, 43.905326], [-79.379778, 43.907319], [-79.378651, 43.910622], [-79.379852, 43.912534], [-79.381294, 43.914909]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_4384e376bf30ca14f5795077ff406f79.bindTooltip(
                `<div>
                     24 WOODBINE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_4384e376bf30ca14f5795077ff406f79.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_ec2fed69e32d056788cab9ce99d144d3_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00AEEF", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_ec2fed69e32d056788cab9ce99d144d3_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_ec2fed69e32d056788cab9ce99d144d3 = L.geoJson(null, {
                onEachFeature: geo_json_ec2fed69e32d056788cab9ce99d144d3_onEachFeature,
            
                style: geo_json_ec2fed69e32d056788cab9ce99d144d3_styler,
            ...{
}
        });

        function geo_json_ec2fed69e32d056788cab9ce99d144d3_add (data) {
            geo_json_ec2fed69e32d056788cab9ce99d144d3
                .addData(data);
        }
            geo_json_ec2fed69e32d056788cab9ce99d144d3_add({"features": [{"geometry": {"coordinates": [[-79.346338, 43.775808], [-79.342943, 43.775868], [-79.335479, 43.775481], [-79.330541, 43.774949], [-79.32708, 43.774577], [-79.324141, 43.778067], [-79.325214, 43.780213], [-79.326271, 43.782417], [-79.32721, 43.784493], [-79.327918, 43.785976], [-79.329384, 43.789098], [-79.330595, 43.791619], [-79.331074, 43.792839], [-79.332558, 43.795926], [-79.333396, 43.797923], [-79.334544, 43.800381], [-79.336078, 43.803901], [-79.337021, 43.805979], [-79.338118, 43.808407], [-79.338907, 43.810277], [-79.339966, 43.813025], [-79.341003, 43.815216], [-79.341823, 43.816952], [-79.342479, 43.818425], [-79.343213, 43.819458], [-79.344535, 43.820974], [-79.347202, 43.822766], [-79.350357, 43.822295], [-79.351427, 43.825126], [-79.352756, 43.830119], [-79.353133, 43.831433], [-79.354166, 43.835338], [-79.354714, 43.837472], [-79.356215, 43.843412], [-79.356842, 43.845656], [-79.357702, 43.849333], [-79.358911, 43.853826], [-79.359677, 43.856597], [-79.360414, 43.859277], [-79.361656, 43.864216], [-79.362576, 43.867763], [-79.363442, 43.871385], [-79.364502, 43.875561], [-79.368041, 43.876536], [-79.371399, 43.876124], [-79.374667, 43.875692], [-79.376019, 43.879652], [-79.373417, 43.880705], [-79.37246, 43.88218], [-79.372981, 43.884523], [-79.370487, 43.885128], [-79.36778, 43.88568], [-79.362196, 43.888581], [-79.363709, 43.890459], [-79.365412, 43.892558], [-79.365922, 43.89377], [-79.367608, 43.896948], [-79.36953, 43.896778], [-79.371269, 43.896769], [-79.372906, 43.896763], [-79.376758, 43.896583], [-79.378487, 43.896996], [-79.377247, 43.899746], [-79.377272, 43.901278], [-79.378938, 43.905326], [-79.379778, 43.907319], [-79.378651, 43.910622], [-79.379852, 43.912534], [-79.381294, 43.914909]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_ec2fed69e32d056788cab9ce99d144d3.bindTooltip(
                `<div>
                     24 WOODBINE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_ec2fed69e32d056788cab9ce99d144d3.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_7159973fb28d4367182287d7f6815f74_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00AEEF", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_7159973fb28d4367182287d7f6815f74_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_7159973fb28d4367182287d7f6815f74 = L.geoJson(null, {
                onEachFeature: geo_json_7159973fb28d4367182287d7f6815f74_onEachFeature,
            
                style: geo_json_7159973fb28d4367182287d7f6815f74_styler,
            ...{
}
        });

        function geo_json_7159973fb28d4367182287d7f6815f74_add (data) {
            geo_json_7159973fb28d4367182287d7f6815f74
                .addData(data);
        }
            geo_json_7159973fb28d4367182287d7f6815f74_add({"features": [{"geometry": {"coordinates": [[-79.381294, 43.914909], [-79.380689, 43.912733], [-79.378322, 43.910176], [-79.379528, 43.905808], [-79.378258, 43.903001], [-79.377072, 43.896518], [-79.373312, 43.896581], [-79.370377, 43.896575], [-79.367871, 43.896972], [-79.366251, 43.894185], [-79.36526, 43.89187], [-79.362932, 43.889548], [-79.361844, 43.887451], [-79.366788, 43.886178], [-79.36836, 43.885802], [-79.369982, 43.885476], [-79.373012, 43.883873], [-79.374015, 43.880748], [-79.376179, 43.879721], [-79.374135, 43.875634], [-79.372265, 43.875854], [-79.368658, 43.876342], [-79.365701, 43.876642], [-79.363903, 43.871785], [-79.362975, 43.868053], [-79.362024, 43.864442], [-79.3608, 43.85964], [-79.360139, 43.857021], [-79.359333, 43.854144], [-79.358174, 43.850028], [-79.357292, 43.846146], [-79.355165, 43.837844], [-79.354639, 43.835853], [-79.353594, 43.831869], [-79.35323, 43.830486], [-79.35187, 43.825433], [-79.349745, 43.822193], [-79.346159, 43.822833], [-79.344993, 43.821359], [-79.342749, 43.818571], [-79.341562, 43.815915], [-79.340676, 43.813805], [-79.339372, 43.810755], [-79.338487, 43.80862], [-79.337564, 43.806541], [-79.336629, 43.804311], [-79.334866, 43.800537], [-79.333852, 43.798156], [-79.332894, 43.79609], [-79.331717, 43.79332], [-79.330971, 43.791868], [-79.329791, 43.789359], [-79.328096, 43.785808], [-79.327232, 43.783965], [-79.326542, 43.782507], [-79.32558, 43.780483], [-79.32436, 43.777828], [-79.323302, 43.775518], [-79.326413, 43.774797], [-79.331695, 43.775292], [-79.335693, 43.775748], [-79.34506, 43.775683]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_7159973fb28d4367182287d7f6815f74.bindTooltip(
                `<div>
                     24 WOODBINE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_7159973fb28d4367182287d7f6815f74.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_2839b7c1b63299d14f9d06fd7047dce6_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00AEEF", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_2839b7c1b63299d14f9d06fd7047dce6_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_2839b7c1b63299d14f9d06fd7047dce6 = L.geoJson(null, {
                onEachFeature: geo_json_2839b7c1b63299d14f9d06fd7047dce6_onEachFeature,
            
                style: geo_json_2839b7c1b63299d14f9d06fd7047dce6_styler,
            ...{
}
        });

        function geo_json_2839b7c1b63299d14f9d06fd7047dce6_add (data) {
            geo_json_2839b7c1b63299d14f9d06fd7047dce6
                .addData(data);
        }
            geo_json_2839b7c1b63299d14f9d06fd7047dce6_add({"features": [{"geometry": {"coordinates": [[-79.381294, 43.914909], [-79.380689, 43.912733], [-79.378322, 43.910176], [-79.379528, 43.905808], [-79.378258, 43.903001], [-79.377072, 43.896518], [-79.373312, 43.896581], [-79.370377, 43.896575], [-79.367871, 43.896972], [-79.366251, 43.894185], [-79.36526, 43.89187], [-79.362932, 43.889548], [-79.361844, 43.887451], [-79.366788, 43.886178], [-79.36836, 43.885802], [-79.369982, 43.885476], [-79.373012, 43.883873], [-79.374015, 43.880748], [-79.376179, 43.879721], [-79.374135, 43.875634], [-79.372265, 43.875854], [-79.368658, 43.876342], [-79.365701, 43.876642], [-79.363903, 43.871785], [-79.362975, 43.868053], [-79.362024, 43.864442], [-79.3608, 43.85964], [-79.362471, 43.858422], [-79.361693, 43.856428], [-79.364879, 43.85465], [-79.366978, 43.85415], [-79.367102, 43.851836], [-79.364187, 43.847806], [-79.364429, 43.846326], [-79.36632, 43.84485], [-79.364935, 43.843354], [-79.362305, 43.843118], [-79.360273, 43.843403], [-79.35907, 43.845213], [-79.357463, 43.845756], [-79.355165, 43.837844], [-79.354639, 43.835853], [-79.353594, 43.831869], [-79.35323, 43.830486], [-79.35187, 43.825433], [-79.349745, 43.822193], [-79.346159, 43.822833], [-79.344993, 43.821359], [-79.342749, 43.818571], [-79.341562, 43.815915], [-79.340676, 43.813805], [-79.339372, 43.810755], [-79.338487, 43.80862], [-79.337564, 43.806541], [-79.336629, 43.804311], [-79.334866, 43.800537], [-79.333852, 43.798156], [-79.332894, 43.79609], [-79.331717, 43.79332], [-79.330971, 43.791868], [-79.329791, 43.789359], [-79.328096, 43.785808], [-79.327232, 43.783965], [-79.326542, 43.782507], [-79.32558, 43.780483], [-79.32436, 43.777828], [-79.323302, 43.775518], [-79.326413, 43.774797], [-79.331695, 43.775292], [-79.335693, 43.775748], [-79.34506, 43.775683]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_2839b7c1b63299d14f9d06fd7047dce6.bindTooltip(
                `<div>
                     24 WOODBINE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_2839b7c1b63299d14f9d06fd7047dce6.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_c21359b6a1645f973c283845b3d602db_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#BD5B5E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_c21359b6a1645f973c283845b3d602db_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_c21359b6a1645f973c283845b3d602db = L.geoJson(null, {
                onEachFeature: geo_json_c21359b6a1645f973c283845b3d602db_onEachFeature,
            
                style: geo_json_c21359b6a1645f973c283845b3d602db_styler,
            ...{
}
        });

        function geo_json_c21359b6a1645f973c283845b3d602db_add (data) {
            geo_json_c21359b6a1645f973c283845b3d602db
                .addData(data);
        }
            geo_json_c21359b6a1645f973c283845b3d602db_add({"features": [{"geometry": {"coordinates": [[-79.231369, 43.880224], [-79.229019, 43.878971], [-79.219933, 43.881999], [-79.220874, 43.884107], [-79.218168, 43.885793], [-79.218709, 43.887843], [-79.220213, 43.89105], [-79.219337, 43.893314], [-79.219657, 43.89618], [-79.221459, 43.896189], [-79.223223, 43.896422], [-79.223773, 43.89717], [-79.22416, 43.898799], [-79.220863, 43.900114], [-79.235346, 43.904667], [-79.239865, 43.905171], [-79.244416, 43.908125], [-79.251047, 43.910937], [-79.257492, 43.912045], [-79.269161, 43.909726], [-79.27349, 43.908506], [-79.277797, 43.907453], [-79.285511, 43.90563], [-79.288993, 43.904825], [-79.294167, 43.903405], [-79.299292, 43.902149], [-79.30434, 43.900966], [-79.309346, 43.899841], [-79.313893, 43.898771], [-79.318429, 43.897781], [-79.333537, 43.894416], [-79.336632, 43.893695], [-79.340366, 43.892945], [-79.342026, 43.892698], [-79.347249, 43.890942], [-79.361376, 43.887448], [-79.366788, 43.886178], [-79.36836, 43.885802], [-79.369982, 43.885476], [-79.372872, 43.884904], [-79.38031, 43.882048], [-79.385776, 43.882037], [-79.391179, 43.880703], [-79.395855, 43.879422], [-79.400067, 43.8785], [-79.406142, 43.877191], [-79.411998, 43.876305], [-79.415047, 43.876239], [-79.416725, 43.875857], [-79.420892, 43.874917], [-79.425135, 43.874038], [-79.427908, 43.873424], [-79.430266, 43.872892], [-79.433853, 43.872082], [-79.436912, 43.871414], [-79.44391, 43.869902], [-79.448577, 43.867894], [-79.445925, 43.867271], [-79.440345, 43.866141], [-79.43751, 43.86933]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_c21359b6a1645f973c283845b3d602db.bindTooltip(
                `<div>
                     25 MAJOR MACKENZIE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_c21359b6a1645f973c283845b3d602db.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_edde0de087c83821d4609218112ec16d_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#BD5B5E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_edde0de087c83821d4609218112ec16d_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_edde0de087c83821d4609218112ec16d = L.geoJson(null, {
                onEachFeature: geo_json_edde0de087c83821d4609218112ec16d_onEachFeature,
            
                style: geo_json_edde0de087c83821d4609218112ec16d_styler,
            ...{
}
        });

        function geo_json_edde0de087c83821d4609218112ec16d_add (data) {
            geo_json_edde0de087c83821d4609218112ec16d
                .addData(data);
        }
            geo_json_edde0de087c83821d4609218112ec16d_add({"features": [{"geometry": {"coordinates": [[-79.43751, 43.86933], [-79.437973, 43.866432], [-79.440378, 43.866219], [-79.445492, 43.867447], [-79.448628, 43.868421], [-79.443744, 43.869707], [-79.440822, 43.870331], [-79.437609, 43.871055], [-79.434281, 43.87184], [-79.430302, 43.872728], [-79.428468, 43.873121], [-79.42471, 43.8739], [-79.421289, 43.874668], [-79.418196, 43.875363], [-79.415815, 43.875861], [-79.412503, 43.876103], [-79.406801, 43.876794], [-79.400789, 43.878096], [-79.39694, 43.878923], [-79.392005, 43.880199], [-79.386694, 43.881611], [-79.38031, 43.882048], [-79.373531, 43.884489], [-79.370487, 43.885128], [-79.36778, 43.88568], [-79.361836, 43.887097], [-79.347426, 43.890625], [-79.343621, 43.892157], [-79.340659, 43.892716], [-79.33719, 43.89339], [-79.334108, 43.894061], [-79.321227, 43.89695], [-79.319462, 43.897339], [-79.314331, 43.898458], [-79.309919, 43.899471], [-79.304959, 43.900614], [-79.299732, 43.901837], [-79.293526, 43.903353], [-79.289698, 43.904447], [-79.286528, 43.905177], [-79.282835, 43.906053], [-79.278404, 43.90711], [-79.273045, 43.908408], [-79.268437, 43.909737], [-79.258547, 43.912214], [-79.251739, 43.910663], [-79.244943, 43.908562], [-79.241119, 43.905131], [-79.235788, 43.904565], [-79.218105, 43.900935], [-79.224368, 43.899053], [-79.224081, 43.89788], [-79.22374, 43.896511], [-79.221738, 43.896094], [-79.219941, 43.896313], [-79.219388, 43.893579], [-79.220447, 43.891256], [-79.219002, 43.888137], [-79.218388, 43.885948], [-79.22073, 43.884324], [-79.220416, 43.882328], [-79.231369, 43.880224]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_edde0de087c83821d4609218112ec16d.bindTooltip(
                `<div>
                     25 MAJOR MACKENZIE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_edde0de087c83821d4609218112ec16d.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_e825616e510666277edf54c7c47974d9_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#BD5B5E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_e825616e510666277edf54c7c47974d9_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_e825616e510666277edf54c7c47974d9 = L.geoJson(null, {
                onEachFeature: geo_json_e825616e510666277edf54c7c47974d9_onEachFeature,
            
                style: geo_json_e825616e510666277edf54c7c47974d9_styler,
            ...{
}
        });

        function geo_json_e825616e510666277edf54c7c47974d9_add (data) {
            geo_json_e825616e510666277edf54c7c47974d9
                .addData(data);
        }
            geo_json_e825616e510666277edf54c7c47974d9_add({"features": [{"geometry": {"coordinates": [[-79.36836, 43.885802], [-79.369982, 43.885476], [-79.372872, 43.884904], [-79.38031, 43.882048], [-79.385776, 43.882037], [-79.391179, 43.880703], [-79.395855, 43.879422], [-79.400067, 43.8785], [-79.406142, 43.877191], [-79.411998, 43.876305], [-79.415047, 43.876239], [-79.416725, 43.875857], [-79.420892, 43.874917], [-79.425135, 43.874038], [-79.427908, 43.873424], [-79.430266, 43.872892], [-79.433853, 43.872082], [-79.436912, 43.871414], [-79.44391, 43.869902], [-79.448577, 43.867894], [-79.445925, 43.867271], [-79.440345, 43.866141], [-79.43751, 43.86933]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_e825616e510666277edf54c7c47974d9.bindTooltip(
                `<div>
                     25 MAJOR MACKENZIE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_e825616e510666277edf54c7c47974d9.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_68bab9a684a6fe464eadce84220a09d0_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#3EC7F4", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_68bab9a684a6fe464eadce84220a09d0_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_68bab9a684a6fe464eadce84220a09d0 = L.geoJson(null, {
                onEachFeature: geo_json_68bab9a684a6fe464eadce84220a09d0_onEachFeature,
            
                style: geo_json_68bab9a684a6fe464eadce84220a09d0_styler,
            ...{
}
        });

        function geo_json_68bab9a684a6fe464eadce84220a09d0_add (data) {
            geo_json_68bab9a684a6fe464eadce84220a09d0
                .addData(data);
        }
            geo_json_68bab9a684a6fe464eadce84220a09d0_add({"features": [{"geometry": {"coordinates": [[-79.527842, 43.796689], [-79.53258, 43.796871], [-79.53383, 43.800031], [-79.534578, 43.801925], [-79.535387, 43.804692], [-79.536233, 43.807826], [-79.537421, 43.809964], [-79.537876, 43.811166], [-79.538528, 43.812825], [-79.539272, 43.815061], [-79.539161, 43.816977], [-79.538805, 43.820118], [-79.539041, 43.821646], [-79.536888, 43.823275], [-79.534094, 43.826885], [-79.530415, 43.827745], [-79.529969, 43.825516], [-79.52714, 43.824416], [-79.524027, 43.82485], [-79.522692, 43.827681], [-79.522426, 43.83453], [-79.525604, 43.838385], [-79.52895, 43.840137], [-79.53006, 43.84233], [-79.530307, 43.843611], [-79.530617, 43.846546], [-79.531081, 43.848272], [-79.531689, 43.850142], [-79.532953, 43.853905], [-79.534006, 43.858262], [-79.539611, 43.856999], [-79.541733, 43.856733], [-79.544107, 43.856469], [-79.547137, 43.856022], [-79.548354, 43.858275], [-79.546471, 43.85973], [-79.543865, 43.86142], [-79.540371, 43.862437], [-79.535406, 43.862855], [-79.53004, 43.865088], [-79.525784, 43.86171], [-79.524015, 43.858874], [-79.519793, 43.85999], [-79.51437, 43.860881], [-79.511085, 43.861488], [-79.50513, 43.862843], [-79.502518, 43.860772], [-79.50618, 43.85979]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_68bab9a684a6fe464eadce84220a09d0.bindTooltip(
                `<div>
                     26 MAPLE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_68bab9a684a6fe464eadce84220a09d0.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_fca2193d5396d409ff35c98484a962cc_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#3EC7F4", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_fca2193d5396d409ff35c98484a962cc_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_fca2193d5396d409ff35c98484a962cc = L.geoJson(null, {
                onEachFeature: geo_json_fca2193d5396d409ff35c98484a962cc_onEachFeature,
            
                style: geo_json_fca2193d5396d409ff35c98484a962cc_styler,
            ...{
}
        });

        function geo_json_fca2193d5396d409ff35c98484a962cc_add (data) {
            geo_json_fca2193d5396d409ff35c98484a962cc
                .addData(data);
        }
            geo_json_fca2193d5396d409ff35c98484a962cc_add({"features": [{"geometry": {"coordinates": [[-79.50618, 43.85979], [-79.511168, 43.861626], [-79.513409, 43.861157], [-79.519195, 43.860255], [-79.523087, 43.858739], [-79.52569, 43.861794], [-79.530141, 43.865214], [-79.534811, 43.863432], [-79.538804, 43.862774], [-79.543344, 43.861699], [-79.546593, 43.859781], [-79.548248, 43.858524], [-79.547419, 43.855994], [-79.544393, 43.85634], [-79.542101, 43.856604], [-79.538592, 43.856953], [-79.536018, 43.857388], [-79.533161, 43.858093], [-79.533461, 43.855699], [-79.532877, 43.853064], [-79.532006, 43.850405], [-79.531342, 43.848507], [-79.530933, 43.846959], [-79.530493, 43.8439], [-79.530314, 43.842709], [-79.529151, 43.840125], [-79.526286, 43.838482], [-79.522587, 43.834436], [-79.522827, 43.828376], [-79.524305, 43.825019], [-79.527708, 43.824407], [-79.529761, 43.825629], [-79.529929, 43.82748], [-79.534094, 43.826885], [-79.537811, 43.823452], [-79.539431, 43.821994], [-79.539089, 43.819659], [-79.53932, 43.817398], [-79.539405, 43.815762], [-79.538582, 43.812499], [-79.537937, 43.810728], [-79.536571, 43.808073], [-79.535689, 43.805166], [-79.534909, 43.802218], [-79.534043, 43.800035], [-79.527842, 43.796689]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_fca2193d5396d409ff35c98484a962cc.bindTooltip(
                `<div>
                     26 MAPLE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_fca2193d5396d409ff35c98484a962cc.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_ffd3ec4c15bf6bb1891f8765fd38fd73_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0058A9", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_ffd3ec4c15bf6bb1891f8765fd38fd73_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_ffd3ec4c15bf6bb1891f8765fd38fd73 = L.geoJson(null, {
                onEachFeature: geo_json_ffd3ec4c15bf6bb1891f8765fd38fd73_onEachFeature,
            
                style: geo_json_ffd3ec4c15bf6bb1891f8765fd38fd73_styler,
            ...{
}
        });

        function geo_json_ffd3ec4c15bf6bb1891f8765fd38fd73_add (data) {
            geo_json_ffd3ec4c15bf6bb1891f8765fd38fd73
                .addData(data);
        }
            geo_json_ffd3ec4c15bf6bb1891f8765fd38fd73_add({"features": [{"geometry": {"coordinates": [[-79.487991, 43.970409], [-79.489479, 43.973518], [-79.489746, 43.975434], [-79.486677, 43.976113], [-79.480634, 43.977445], [-79.477578, 43.978116], [-79.470367, 43.97965], [-79.467968, 43.980168], [-79.465463, 43.981815], [-79.463939, 43.983659], [-79.462513, 43.983904], [-79.460005, 43.984794], [-79.459742, 43.987457], [-79.461196, 43.987513], [-79.46417, 43.986829], [-79.466712, 43.986255], [-79.469534, 43.984529], [-79.471923, 43.983832], [-79.47412, 43.983653], [-79.47556, 43.98439], [-79.475993, 43.988578], [-79.479888, 43.990941], [-79.482308, 43.990577], [-79.484897, 43.989993], [-79.487372, 43.989464], [-79.489872, 43.989468], [-79.492884, 43.989197], [-79.49261, 43.994279], [-79.487041, 43.995373], [-79.483445, 43.996087], [-79.479627, 43.996918], [-79.476131, 43.99769], [-79.472723, 43.998455], [-79.46832, 43.999445], [-79.465904, 43.999965], [-79.464299, 44.000311], [-79.460693, 44.001138], [-79.456992, 44.001909], [-79.451138, 44.003193], [-79.444109, 44.004852], [-79.442997, 44.001094]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_ffd3ec4c15bf6bb1891f8765fd38fd73.bindTooltip(
                `<div>
                     32 AURORA SOUTH
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_ffd3ec4c15bf6bb1891f8765fd38fd73.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_dd819691727fcef5e447a28bd91e3d13_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0058A9", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_dd819691727fcef5e447a28bd91e3d13_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_dd819691727fcef5e447a28bd91e3d13 = L.geoJson(null, {
                onEachFeature: geo_json_dd819691727fcef5e447a28bd91e3d13_onEachFeature,
            
                style: geo_json_dd819691727fcef5e447a28bd91e3d13_styler,
            ...{
}
        });

        function geo_json_dd819691727fcef5e447a28bd91e3d13_add (data) {
            geo_json_dd819691727fcef5e447a28bd91e3d13
                .addData(data);
        }
            geo_json_dd819691727fcef5e447a28bd91e3d13_add({"features": [{"geometry": {"coordinates": [[-79.487991, 43.970409], [-79.489479, 43.973518], [-79.489746, 43.975434]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_dd819691727fcef5e447a28bd91e3d13.bindTooltip(
                `<div>
                     32 AURORA SOUTH
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_dd819691727fcef5e447a28bd91e3d13.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_40be5d762108b3cda04a77ccc569f9fb_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0058A9", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_40be5d762108b3cda04a77ccc569f9fb_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_40be5d762108b3cda04a77ccc569f9fb = L.geoJson(null, {
                onEachFeature: geo_json_40be5d762108b3cda04a77ccc569f9fb_onEachFeature,
            
                style: geo_json_40be5d762108b3cda04a77ccc569f9fb_styler,
            ...{
}
        });

        function geo_json_40be5d762108b3cda04a77ccc569f9fb_add (data) {
            geo_json_40be5d762108b3cda04a77ccc569f9fb
                .addData(data);
        }
            geo_json_40be5d762108b3cda04a77ccc569f9fb_add({"features": [{"geometry": {"coordinates": [[-79.456992, 44.001909], [-79.451138, 44.003193], [-79.444109, 44.004852], [-79.442997, 44.001094]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_40be5d762108b3cda04a77ccc569f9fb.bindTooltip(
                `<div>
                     32 AURORA SOUTH
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_40be5d762108b3cda04a77ccc569f9fb.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_43673d4144ba17eb1b6bd9df4bef2dae_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0058A9", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_43673d4144ba17eb1b6bd9df4bef2dae_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_43673d4144ba17eb1b6bd9df4bef2dae = L.geoJson(null, {
                onEachFeature: geo_json_43673d4144ba17eb1b6bd9df4bef2dae_onEachFeature,
            
                style: geo_json_43673d4144ba17eb1b6bd9df4bef2dae_styler,
            ...{
}
        });

        function geo_json_43673d4144ba17eb1b6bd9df4bef2dae_add (data) {
            geo_json_43673d4144ba17eb1b6bd9df4bef2dae
                .addData(data);
        }
            geo_json_43673d4144ba17eb1b6bd9df4bef2dae_add({"features": [{"geometry": {"coordinates": [[-79.442997, 44.001094], [-79.442175, 43.994272], [-79.444056, 43.993853], [-79.446044, 43.993405], [-79.447185, 43.993501], [-79.449104, 43.994221], [-79.447388, 43.997306], [-79.445564, 43.998905], [-79.443694, 44.000706], [-79.444889, 44.004867], [-79.450674, 44.003497], [-79.452112, 44.003147], [-79.454002, 44.002749], [-79.457317, 44.002018], [-79.460502, 44.001278], [-79.463921, 44.000489], [-79.467392, 43.999805], [-79.468527, 43.999496], [-79.472162, 43.998714], [-79.475881, 43.997919], [-79.480009, 43.997046], [-79.483089, 43.996381], [-79.486704, 43.995639], [-79.492878, 43.994429], [-79.4924, 43.989096], [-79.487749, 43.989356], [-79.485338, 43.989813], [-79.481856, 43.990575], [-79.48015, 43.990984], [-79.476192, 43.988621], [-79.476161, 43.985275], [-79.474501, 43.983615], [-79.469866, 43.984286], [-79.466976, 43.986094], [-79.464771, 43.986522], [-79.460181, 43.987588], [-79.460133, 43.984854], [-79.462698, 43.983985], [-79.464687, 43.983672], [-79.465704, 43.982432], [-79.467386, 43.980432], [-79.470662, 43.979728], [-79.476532, 43.978415], [-79.476003, 43.976142], [-79.475298, 43.973752], [-79.477595, 43.972922], [-79.479934, 43.971893], [-79.482522, 43.970926], [-79.484866, 43.970856], [-79.487991, 43.970409]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_43673d4144ba17eb1b6bd9df4bef2dae.bindTooltip(
                `<div>
                     32 AURORA SOUTH
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_43673d4144ba17eb1b6bd9df4bef2dae.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_8302ca73fbf7f2a57e84a5c247c958af_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0058A9", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_8302ca73fbf7f2a57e84a5c247c958af_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_8302ca73fbf7f2a57e84a5c247c958af = L.geoJson(null, {
                onEachFeature: geo_json_8302ca73fbf7f2a57e84a5c247c958af_onEachFeature,
            
                style: geo_json_8302ca73fbf7f2a57e84a5c247c958af_styler,
            ...{
}
        });

        function geo_json_8302ca73fbf7f2a57e84a5c247c958af_add (data) {
            geo_json_8302ca73fbf7f2a57e84a5c247c958af
                .addData(data);
        }
            geo_json_8302ca73fbf7f2a57e84a5c247c958af_add({"features": [{"geometry": {"coordinates": [[-79.442997, 44.001094], [-79.442175, 43.994272], [-79.444056, 43.993853], [-79.446044, 43.993405], [-79.447185, 43.993501], [-79.449104, 43.994221], [-79.447388, 43.997306], [-79.445564, 43.998905], [-79.443694, 44.000706]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_8302ca73fbf7f2a57e84a5c247c958af.bindTooltip(
                `<div>
                     32 AURORA SOUTH
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_8302ca73fbf7f2a57e84a5c247c958af.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_df27c51c7b5461a5d72d7f4af06a4eff_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0058A9", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_df27c51c7b5461a5d72d7f4af06a4eff_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_df27c51c7b5461a5d72d7f4af06a4eff = L.geoJson(null, {
                onEachFeature: geo_json_df27c51c7b5461a5d72d7f4af06a4eff_onEachFeature,
            
                style: geo_json_df27c51c7b5461a5d72d7f4af06a4eff_styler,
            ...{
}
        });

        function geo_json_df27c51c7b5461a5d72d7f4af06a4eff_add (data) {
            geo_json_df27c51c7b5461a5d72d7f4af06a4eff
                .addData(data);
        }
            geo_json_df27c51c7b5461a5d72d7f4af06a4eff_add({"features": [{"geometry": {"coordinates": [[-79.442997, 44.001094], [-79.442175, 43.994272], [-79.444056, 43.993853], [-79.446044, 43.993405], [-79.447185, 43.993501], [-79.449104, 43.994221], [-79.447388, 43.997306], [-79.445564, 43.998905], [-79.443694, 44.000706], [-79.444889, 44.004867], [-79.450674, 44.003497], [-79.452112, 44.003147], [-79.454002, 44.002749], [-79.457317, 44.002018], [-79.460502, 44.001278], [-79.463921, 44.000489], [-79.467392, 43.999805], [-79.468527, 43.999496], [-79.472162, 43.998714], [-79.475881, 43.997919], [-79.480009, 43.997046], [-79.483089, 43.996381], [-79.486704, 43.995639], [-79.492878, 43.994429], [-79.4924, 43.989096], [-79.487749, 43.989356], [-79.485338, 43.989813], [-79.481856, 43.990575], [-79.48015, 43.990984], [-79.476192, 43.988621], [-79.476161, 43.985275], [-79.474501, 43.983615], [-79.469866, 43.984286], [-79.466976, 43.986094], [-79.46446, 43.987502], [-79.461642, 43.99122], [-79.460181, 43.987588], [-79.460133, 43.984854], [-79.462698, 43.983985], [-79.464687, 43.983672], [-79.465704, 43.982432], [-79.467386, 43.980432], [-79.470662, 43.979728], [-79.476532, 43.978415], [-79.476003, 43.976142], [-79.475298, 43.973752], [-79.477595, 43.972922], [-79.479934, 43.971893], [-79.482522, 43.970926], [-79.484866, 43.970856], [-79.487991, 43.970409]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_df27c51c7b5461a5d72d7f4af06a4eff.bindTooltip(
                `<div>
                     32 AURORA SOUTH
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_df27c51c7b5461a5d72d7f4af06a4eff.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_3c175c7dfb436b738e175237dde8cc4f_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00B5CC", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_3c175c7dfb436b738e175237dde8cc4f_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_3c175c7dfb436b738e175237dde8cc4f = L.geoJson(null, {
                onEachFeature: geo_json_3c175c7dfb436b738e175237dde8cc4f_onEachFeature,
            
                style: geo_json_3c175c7dfb436b738e175237dde8cc4f_styler,
            ...{
}
        });

        function geo_json_3c175c7dfb436b738e175237dde8cc4f_add (data) {
            geo_json_3c175c7dfb436b738e175237dde8cc4f
                .addData(data);
        }
            geo_json_3c175c7dfb436b738e175237dde8cc4f_add({"features": [{"geometry": {"coordinates": [[-79.476315, 43.998281], [-79.472723, 43.998455], [-79.46832, 43.999445], [-79.465904, 43.999965], [-79.464299, 44.000311], [-79.460693, 44.001138], [-79.456992, 44.001909], [-79.451138, 44.003193], [-79.444109, 44.004852], [-79.43913, 44.006051], [-79.433487, 44.007329], [-79.425768, 44.009053], [-79.419082, 44.010551], [-79.413945, 44.009005], [-79.414197, 44.01175], [-79.415292, 44.013925], [-79.414373, 44.016093], [-79.410063, 44.018868], [-79.413522, 44.020203], [-79.420338, 44.019789], [-79.422477, 44.028843], [-79.424386, 44.035379], [-79.424851, 44.037145], [-79.42581, 44.040487], [-79.426365, 44.042877], [-79.427388, 44.048048], [-79.427723, 44.04973], [-79.428145, 44.051404], [-79.428779, 44.053827], [-79.429725, 44.057667], [-79.430263, 44.059913], [-79.431174, 44.063293], [-79.431204, 44.065884], [-79.426599, 44.066878], [-79.421016, 44.067146]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_3c175c7dfb436b738e175237dde8cc4f.bindTooltip(
                `<div>
                     33 WELLINGTON - LESLIE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_3c175c7dfb436b738e175237dde8cc4f.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_c758325567fc0535ef6b6b74ecfa2d0d_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00B5CC", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_c758325567fc0535ef6b6b74ecfa2d0d_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_c758325567fc0535ef6b6b74ecfa2d0d = L.geoJson(null, {
                onEachFeature: geo_json_c758325567fc0535ef6b6b74ecfa2d0d_onEachFeature,
            
                style: geo_json_c758325567fc0535ef6b6b74ecfa2d0d_styler,
            ...{
}
        });

        function geo_json_c758325567fc0535ef6b6b74ecfa2d0d_add (data) {
            geo_json_c758325567fc0535ef6b6b74ecfa2d0d
                .addData(data);
        }
            geo_json_c758325567fc0535ef6b6b74ecfa2d0d_add({"features": [{"geometry": {"coordinates": [[-79.421016, 44.067146], [-79.426071, 44.067266], [-79.429516, 44.066488], [-79.431481, 44.063383], [-79.43072, 44.060306], [-79.429811, 44.056968], [-79.429154, 44.054135], [-79.428492, 44.051663], [-79.428066, 44.049958], [-79.427646, 44.047688], [-79.42672, 44.043302], [-79.425317, 44.037637], [-79.424436, 44.034558], [-79.422966, 44.029218], [-79.422143, 44.02578], [-79.414441, 44.020931], [-79.410063, 44.018868], [-79.414314, 44.016538], [-79.415553, 44.01448], [-79.414813, 44.012321], [-79.413515, 44.009358], [-79.42138, 44.010281], [-79.425171, 44.009486], [-79.43301, 44.00775], [-79.439224, 44.0063], [-79.443617, 44.005262], [-79.444889, 44.004867], [-79.450674, 44.003497], [-79.452112, 44.003147], [-79.454002, 44.002749], [-79.457317, 44.002018], [-79.460502, 44.001278], [-79.463921, 44.000489], [-79.467392, 43.999805], [-79.468527, 43.999496], [-79.472162, 43.998714], [-79.475881, 43.997919], [-79.480009, 43.997046], [-79.477638, 43.999191], [-79.476315, 43.998281]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_c758325567fc0535ef6b6b74ecfa2d0d.bindTooltip(
                `<div>
                     33 WELLINGTON - LESLIE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_c758325567fc0535ef6b6b74ecfa2d0d.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_b7db7ea859b13b46c4b5370d85bcd73e_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#806A50", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_b7db7ea859b13b46c4b5370d85bcd73e_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_b7db7ea859b13b46c4b5370d85bcd73e = L.geoJson(null, {
                onEachFeature: geo_json_b7db7ea859b13b46c4b5370d85bcd73e_onEachFeature,
            
                style: geo_json_b7db7ea859b13b46c4b5370d85bcd73e_styler,
            ...{
}
        });

        function geo_json_b7db7ea859b13b46c4b5370d85bcd73e_add (data) {
            geo_json_b7db7ea859b13b46c4b5370d85bcd73e
                .addData(data);
        }
            geo_json_b7db7ea859b13b46c4b5370d85bcd73e_add({"features": [{"geometry": {"coordinates": [[-79.28813, 43.867088], [-79.284976, 43.869598], [-79.285663, 43.872593], [-79.286102, 43.874173], [-79.289463, 43.876546], [-79.291537, 43.875804], [-79.2975, 43.874183], [-79.298981, 43.872615], [-79.300576, 43.871157], [-79.304738, 43.870237], [-79.309549, 43.869119], [-79.312073, 43.868926], [-79.313612, 43.869788], [-79.316283, 43.871618], [-79.318583, 43.872267], [-79.32192, 43.871533], [-79.323572, 43.871186], [-79.328063, 43.870994], [-79.328023, 43.867853], [-79.326818, 43.865813], [-79.326193, 43.863634], [-79.329801, 43.86326], [-79.333283, 43.862332], [-79.333015, 43.860656], [-79.334075, 43.860161], [-79.334722, 43.85814], [-79.334172, 43.856002], [-79.339009, 43.854388], [-79.339811, 43.855282], [-79.339349, 43.857519], [-79.338642, 43.85988], [-79.338482, 43.86158], [-79.339522, 43.864592], [-79.340041, 43.866439], [-79.34182, 43.867767], [-79.343789, 43.868159], [-79.347602, 43.867986], [-79.349411, 43.867433], [-79.352386, 43.86993], [-79.35487, 43.871832], [-79.356833, 43.872927], [-79.359846, 43.872207], [-79.363383, 43.871714], [-79.364502, 43.875561], [-79.364737, 43.876569], [-79.364004, 43.876817], [-79.362234, 43.87708], [-79.360496, 43.877173], [-79.358776, 43.876642], [-79.357482, 43.874949], [-79.356229, 43.873223], [-79.355096, 43.871826], [-79.352846, 43.870326], [-79.350799, 43.867086], [-79.352495, 43.866379], [-79.356051, 43.86549], [-79.358915, 43.864439], [-79.357361, 43.861652], [-79.355642, 43.860756], [-79.353224, 43.85907], [-79.349392, 43.859099], [-79.344633, 43.860163], [-79.342172, 43.860386], [-79.339074, 43.860084], [-79.339541, 43.857864], [-79.339915, 43.854869], [-79.334236, 43.857664], [-79.334751, 43.859694], [-79.332993, 43.86033], [-79.333338, 43.862107], [-79.329693, 43.86314], [-79.326341, 43.863429], [-79.326258, 43.865153], [-79.327956, 43.8682], [-79.32799, 43.870897], [-79.324121, 43.870995], [-79.320854, 43.871651], [-79.318459, 43.872183], [-79.316499, 43.871588], [-79.314253, 43.870154], [-79.31258, 43.868936], [-79.309346, 43.869029], [-79.305361, 43.869885], [-79.300928, 43.870907], [-79.299012, 43.87234], [-79.297536, 43.873966], [-79.291864, 43.875576], [-79.287177, 43.876898], [-79.286547, 43.875043], [-79.286105, 43.872935], [-79.285414, 43.870054], [-79.284737, 43.867374], [-79.28813, 43.867088]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_b7db7ea859b13b46c4b5370d85bcd73e.bindTooltip(
                `<div>
                     40 UNIONVILLE LOCAL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_b7db7ea859b13b46c4b5370d85bcd73e.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_1f5a89fa451db458f339ee06527cdf72_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#66A6BC", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_1f5a89fa451db458f339ee06527cdf72_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_1f5a89fa451db458f339ee06527cdf72 = L.geoJson(null, {
                onEachFeature: geo_json_1f5a89fa451db458f339ee06527cdf72_onEachFeature,
            
                style: geo_json_1f5a89fa451db458f339ee06527cdf72_styler,
            ...{
}
        });

        function geo_json_1f5a89fa451db458f339ee06527cdf72_add (data) {
            geo_json_1f5a89fa451db458f339ee06527cdf72
                .addData(data);
        }
            geo_json_1f5a89fa451db458f339ee06527cdf72_add({"features": [{"geometry": {"coordinates": [[-79.486673, 44.052774], [-79.48617, 44.054512], [-79.490529, 44.052823], [-79.496797, 44.051409], [-79.497916, 44.052841], [-79.499455, 44.056179], [-79.495708, 44.056696], [-79.493721, 44.058153], [-79.492169, 44.059548], [-79.492496, 44.062926], [-79.493228, 44.065905], [-79.493773, 44.068252], [-79.493941, 44.070713], [-79.485451, 44.072654], [-79.484559, 44.071102], [-79.482029, 44.068211], [-79.477738, 44.068247], [-79.474999, 44.069128], [-79.47113, 44.069557], [-79.468888, 44.067387], [-79.470899, 44.065514], [-79.473182, 44.064527], [-79.475497, 44.064005], [-79.473702, 44.060804], [-79.471943, 44.057943], [-79.474401, 44.056351], [-79.477758, 44.055598], [-79.479985, 44.055123], [-79.483716, 44.054279], [-79.486673, 44.052774]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_1f5a89fa451db458f339ee06527cdf72.bindTooltip(
                `<div>
                     44 BRISTOL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_1f5a89fa451db458f339ee06527cdf72.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_9f2768132e67145f28cf90f553916920_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#684287", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_9f2768132e67145f28cf90f553916920_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_9f2768132e67145f28cf90f553916920 = L.geoJson(null, {
                onEachFeature: geo_json_9f2768132e67145f28cf90f553916920_onEachFeature,
            
                style: geo_json_9f2768132e67145f28cf90f553916920_styler,
            ...{
}
        });

        function geo_json_9f2768132e67145f28cf90f553916920_add (data) {
            geo_json_9f2768132e67145f28cf90f553916920
                .addData(data);
        }
            geo_json_9f2768132e67145f28cf90f553916920_add({"features": [{"geometry": {"coordinates": [[-79.486234, 44.052604], [-79.485781, 44.053567], [-79.483007, 44.054155], [-79.48074, 44.054598], [-79.478129, 44.055201], [-79.474817, 44.055928], [-79.472341, 44.05651], [-79.468047, 44.057485], [-79.465736, 44.057986], [-79.463903, 44.058407], [-79.461437, 44.058931], [-79.458961, 44.059392], [-79.455828, 44.060245], [-79.454515, 44.06049], [-79.452712, 44.060904], [-79.449566, 44.061604], [-79.445031, 44.062665], [-79.439231, 44.064038], [-79.436119, 44.064749], [-79.431973, 44.06657], [-79.432338, 44.067728], [-79.432716, 44.069652], [-79.433685, 44.073449], [-79.434373, 44.076295], [-79.43522, 44.079483], [-79.436362, 44.083902], [-79.43862, 44.092573], [-79.439664, 44.096663], [-79.44043, 44.099704], [-79.441029, 44.102008], [-79.441986, 44.105862], [-79.445018, 44.117524], [-79.447161, 44.125787], [-79.448732, 44.131974], [-79.449518, 44.135002], [-79.450405, 44.138426], [-79.451503, 44.142713], [-79.455103, 44.156876], [-79.459685, 44.175086], [-79.464181, 44.193089], [-79.464685, 44.195363], [-79.465477, 44.198763], [-79.466329, 44.20179], [-79.467198, 44.205099], [-79.466741, 44.20866], [-79.464901, 44.21207], [-79.461788, 44.212895], [-79.460237, 44.213252], [-79.447218, 44.218081], [-79.447536, 44.216247], [-79.459865, 44.213462], [-79.46205, 44.212986], [-79.464542, 44.214682], [-79.464309, 44.216522], [-79.465149, 44.219126], [-79.465328, 44.223358], [-79.464237, 44.225852], [-79.465149, 44.229155], [-79.465517, 44.233075], [-79.463812, 44.236721], [-79.463601, 44.238479], [-79.465666, 44.240644], [-79.468331, 44.241708], [-79.470541, 44.242708], [-79.472934, 44.242209], [-79.474317, 44.241507], [-79.476357, 44.242622], [-79.478584, 44.244458], [-79.480603, 44.246126], [-79.483509, 44.248536], [-79.485641, 44.251115], [-79.485724, 44.253436], [-79.484863, 44.258029], [-79.488473, 44.266466], [-79.497639, 44.27209], [-79.484519, 44.28652], [-79.472189, 44.297308], [-79.466224, 44.301479], [-79.459257, 44.30351], [-79.44152, 44.307017], [-79.427453, 44.309998], [-79.42198, 44.311062], [-79.419489, 44.311525], [-79.416863, 44.312081], [-79.410338, 44.313371], [-79.403728, 44.314674], [-79.396484, 44.316102], [-79.392315, 44.316927], [-79.388144, 44.317728], [-79.385352, 44.318274], [-79.381186, 44.31914], [-79.378232, 44.319671], [-79.374637, 44.320398], [-79.370801, 44.321215], [-79.369552, 44.319386], [-79.368682, 44.317574], [-79.367518, 44.315088], [-79.366539, 44.312744], [-79.365531, 44.310325], [-79.364257, 44.307415], [-79.362143, 44.3046], [-79.357261, 44.302883], [-79.355529, 44.301785], [-79.352733, 44.299615]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_9f2768132e67145f28cf90f553916920.bindTooltip(
                `<div>
                     50 QUEENSWAY
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_9f2768132e67145f28cf90f553916920.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_f5f9e4fe722a5a36f246036cf7551f98_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#684287", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_f5f9e4fe722a5a36f246036cf7551f98_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_f5f9e4fe722a5a36f246036cf7551f98 = L.geoJson(null, {
                onEachFeature: geo_json_f5f9e4fe722a5a36f246036cf7551f98_onEachFeature,
            
                style: geo_json_f5f9e4fe722a5a36f246036cf7551f98_styler,
            ...{
}
        });

        function geo_json_f5f9e4fe722a5a36f246036cf7551f98_add (data) {
            geo_json_f5f9e4fe722a5a36f246036cf7551f98
                .addData(data);
        }
            geo_json_f5f9e4fe722a5a36f246036cf7551f98_add({"features": [{"geometry": {"coordinates": [[-79.352733, 44.299615], [-79.355254, 44.301796], [-79.357424, 44.303141], [-79.362281, 44.304667], [-79.364114, 44.307612], [-79.365022, 44.309742], [-79.366529, 44.313486], [-79.367412, 44.315114], [-79.368514, 44.317604], [-79.369147, 44.319468], [-79.370737, 44.32131], [-79.374559, 44.320523], [-79.37785, 44.319849], [-79.380955, 44.319297], [-79.385234, 44.318416], [-79.388111, 44.31785], [-79.392287, 44.317041], [-79.396493, 44.316199], [-79.403745, 44.314773], [-79.41039, 44.313452], [-79.416306, 44.312306], [-79.419267, 44.311715], [-79.421921, 44.311217], [-79.42737, 44.310084], [-79.441045, 44.307414], [-79.45894, 44.303924], [-79.465525, 44.3019], [-79.47074, 44.298819], [-79.484259, 44.28687], [-79.497779, 44.272], [-79.488748, 44.266371], [-79.484939, 44.258087], [-79.485746, 44.254069], [-79.485874, 44.251559], [-79.484233, 44.248838], [-79.480532, 44.245952], [-79.479096, 44.244704], [-79.477037, 44.243042], [-79.474026, 44.241546], [-79.472568, 44.242134], [-79.470814, 44.242513], [-79.468278, 44.241549], [-79.465805, 44.240619], [-79.463778, 44.238594], [-79.463878, 44.23686], [-79.465785, 44.232903], [-79.465366, 44.229109], [-79.464469, 44.225835], [-79.465733, 44.223007], [-79.465247, 44.218881], [-79.464543, 44.216168], [-79.461788, 44.212895], [-79.460237, 44.213252], [-79.447218, 44.218081], [-79.447536, 44.216247], [-79.459865, 44.213462], [-79.46205, 44.212986], [-79.46661, 44.209188], [-79.467495, 44.205378], [-79.466514, 44.201387], [-79.466076, 44.199701], [-79.465518, 44.197545], [-79.464578, 44.193407], [-79.46423, 44.192072], [-79.45998, 44.175265], [-79.455228, 44.15703], [-79.45177, 44.143012], [-79.450585, 44.138368], [-79.449653, 44.134902], [-79.448845, 44.131921], [-79.447285, 44.125751], [-79.445221, 44.117617], [-79.442264, 44.106107], [-79.441455, 44.102526], [-79.440615, 44.099566], [-79.439953, 44.097201], [-79.438819, 44.092674], [-79.436818, 44.084337], [-79.43564, 44.079877], [-79.43482, 44.076712], [-79.434061, 44.07379], [-79.433443, 44.071444], [-79.433106, 44.070004], [-79.432516, 44.067675], [-79.43215, 44.066035], [-79.432667, 44.065766], [-79.434913, 44.065165], [-79.43704, 44.064718], [-79.438898, 44.064312], [-79.445579, 44.062777], [-79.449215, 44.061995], [-79.45184, 44.061384], [-79.454082, 44.060876], [-79.456139, 44.060444], [-79.459338, 44.05966], [-79.461761, 44.059179], [-79.463488, 44.058764], [-79.465752, 44.05828], [-79.467995, 44.05774], [-79.47188, 44.056898], [-79.474401, 44.056351], [-79.477758, 44.055598], [-79.479985, 44.055123], [-79.483716, 44.054279], [-79.486234, 44.052604]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_f5f9e4fe722a5a36f246036cf7551f98.bindTooltip(
                `<div>
                     50 QUEENSWAY
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_f5f9e4fe722a5a36f246036cf7551f98.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_416ff7a938635ae8f6bae0e21e3eaf2a_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#DC62A5", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_416ff7a938635ae8f6bae0e21e3eaf2a_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_416ff7a938635ae8f6bae0e21e3eaf2a = L.geoJson(null, {
                onEachFeature: geo_json_416ff7a938635ae8f6bae0e21e3eaf2a_onEachFeature,
            
                style: geo_json_416ff7a938635ae8f6bae0e21e3eaf2a_styler,
            ...{
}
        });

        function geo_json_416ff7a938635ae8f6bae0e21e3eaf2a_add (data) {
            geo_json_416ff7a938635ae8f6bae0e21e3eaf2a
                .addData(data);
        }
            geo_json_416ff7a938635ae8f6bae0e21e3eaf2a_add({"features": [{"geometry": {"coordinates": [[-79.443831, 44.209331], [-79.460238, 44.194318], [-79.464175, 44.193456], [-79.464685, 44.195363], [-79.465477, 44.198763], [-79.466329, 44.20179], [-79.467198, 44.205099], [-79.466741, 44.20866], [-79.464901, 44.21207], [-79.464542, 44.214682], [-79.464309, 44.216522], [-79.465149, 44.219126], [-79.465328, 44.223358], [-79.462592, 44.223566], [-79.459018, 44.222849], [-79.453659, 44.222855], [-79.451599, 44.223328], [-79.447067, 44.225064], [-79.447279, 44.228758], [-79.448077, 44.232006], [-79.448582, 44.234018], [-79.449232, 44.236411], [-79.451398, 44.24036], [-79.455008, 44.240077], [-79.457011, 44.243205], [-79.461566, 44.243696], [-79.460841, 44.240686], [-79.463601, 44.238479], [-79.465666, 44.240644], [-79.468331, 44.241708], [-79.470541, 44.242708], [-79.472934, 44.242209], [-79.474317, 44.241507], [-79.470912, 44.237937], [-79.467643, 44.235232], [-79.465785, 44.232903], [-79.465366, 44.229109], [-79.464469, 44.225835], [-79.465733, 44.223007], [-79.465247, 44.218881], [-79.464543, 44.216168], [-79.461788, 44.212895], [-79.460237, 44.213252], [-79.447218, 44.218081], [-79.443831, 44.209331]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_416ff7a938635ae8f6bae0e21e3eaf2a.bindTooltip(
                `<div>
                     51 KESWICK
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_416ff7a938635ae8f6bae0e21e3eaf2a.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_bce9d06e412071831b79f0e93e1cd937_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A54686", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_bce9d06e412071831b79f0e93e1cd937_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_bce9d06e412071831b79f0e93e1cd937 = L.geoJson(null, {
                onEachFeature: geo_json_bce9d06e412071831b79f0e93e1cd937_onEachFeature,
            
                style: geo_json_bce9d06e412071831b79f0e93e1cd937_styler,
            ...{
}
        });

        function geo_json_bce9d06e412071831b79f0e93e1cd937_add (data) {
            geo_json_bce9d06e412071831b79f0e93e1cd937
                .addData(data);
        }
            geo_json_bce9d06e412071831b79f0e93e1cd937_add({"features": [{"geometry": {"coordinates": [[-79.487077, 44.053076], [-79.48104, 44.05851], [-79.481709, 44.060872], [-79.48247, 44.064102], [-79.483384, 44.067795], [-79.484137, 44.070723], [-79.484586, 44.072714], [-79.485546, 44.076645], [-79.487152, 44.082909], [-79.489949, 44.095346], [-79.490539, 44.097626], [-79.491401, 44.101178], [-79.492225, 44.104226], [-79.492458, 44.10541], [-79.492094, 44.109966], [-79.492816, 44.113506], [-79.49365, 44.116918], [-79.494544, 44.120328], [-79.495662, 44.125342], [-79.49629, 44.12799], [-79.498267, 44.12792]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_bce9d06e412071831b79f0e93e1cd937.bindTooltip(
                `<div>
                     52 HOLLAND LANDING
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_bce9d06e412071831b79f0e93e1cd937.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_154c931965591067c51ed72ab93a3316_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A54686", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_154c931965591067c51ed72ab93a3316_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_154c931965591067c51ed72ab93a3316 = L.geoJson(null, {
                onEachFeature: geo_json_154c931965591067c51ed72ab93a3316_onEachFeature,
            
                style: geo_json_154c931965591067c51ed72ab93a3316_styler,
            ...{
}
        });

        function geo_json_154c931965591067c51ed72ab93a3316_add (data) {
            geo_json_154c931965591067c51ed72ab93a3316
                .addData(data);
        }
            geo_json_154c931965591067c51ed72ab93a3316_add({"features": [{"geometry": {"coordinates": [[-79.489949, 44.095346], [-79.490539, 44.097626], [-79.491401, 44.101178], [-79.492225, 44.104226], [-79.492458, 44.10541], [-79.492094, 44.109966], [-79.492816, 44.113506], [-79.49365, 44.116918], [-79.494544, 44.120328], [-79.495662, 44.125342], [-79.49629, 44.12799], [-79.498267, 44.12792]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_154c931965591067c51ed72ab93a3316.bindTooltip(
                `<div>
                     52 HOLLAND LANDING
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_154c931965591067c51ed72ab93a3316.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_b804081bc0f15dd4d6a95f820df6c762_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A54686", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_b804081bc0f15dd4d6a95f820df6c762_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_b804081bc0f15dd4d6a95f820df6c762 = L.geoJson(null, {
                onEachFeature: geo_json_b804081bc0f15dd4d6a95f820df6c762_onEachFeature,
            
                style: geo_json_b804081bc0f15dd4d6a95f820df6c762_styler,
            ...{
}
        });

        function geo_json_b804081bc0f15dd4d6a95f820df6c762_add (data) {
            geo_json_b804081bc0f15dd4d6a95f820df6c762
                .addData(data);
        }
            geo_json_b804081bc0f15dd4d6a95f820df6c762_add({"features": [{"geometry": {"coordinates": [[-79.487077, 44.053076], [-79.487795, 44.055565], [-79.486494, 44.058291], [-79.48104, 44.05851], [-79.481709, 44.060872], [-79.48247, 44.064102], [-79.483384, 44.067795], [-79.484137, 44.070723], [-79.484586, 44.072714], [-79.485546, 44.076645], [-79.487152, 44.082909], [-79.489949, 44.095346], [-79.490539, 44.097626], [-79.491401, 44.101178], [-79.492225, 44.104226], [-79.492458, 44.10541], [-79.492094, 44.109966], [-79.492816, 44.113506], [-79.49365, 44.116918], [-79.494544, 44.120328], [-79.495662, 44.125342], [-79.49629, 44.12799], [-79.498267, 44.12792]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_b804081bc0f15dd4d6a95f820df6c762.bindTooltip(
                `<div>
                     52 HOLLAND LANDING
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_b804081bc0f15dd4d6a95f820df6c762.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_c336cf023a3176247bd1b6098ed3ac6f_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A54686", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_c336cf023a3176247bd1b6098ed3ac6f_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_c336cf023a3176247bd1b6098ed3ac6f = L.geoJson(null, {
                onEachFeature: geo_json_c336cf023a3176247bd1b6098ed3ac6f_onEachFeature,
            
                style: geo_json_c336cf023a3176247bd1b6098ed3ac6f_styler,
            ...{
}
        });

        function geo_json_c336cf023a3176247bd1b6098ed3ac6f_add (data) {
            geo_json_c336cf023a3176247bd1b6098ed3ac6f
                .addData(data);
        }
            geo_json_c336cf023a3176247bd1b6098ed3ac6f_add({"features": [{"geometry": {"coordinates": [[-79.487077, 44.053076], [-79.487795, 44.055565], [-79.486494, 44.058291], [-79.48104, 44.05851], [-79.481709, 44.060872], [-79.48247, 44.064102], [-79.483384, 44.067795], [-79.484137, 44.070723], [-79.484586, 44.072714], [-79.485546, 44.076645], [-79.487152, 44.082909], [-79.489949, 44.095346], [-79.486483, 44.095834], [-79.482223, 44.096726], [-79.47798, 44.097649], [-79.474087, 44.098303], [-79.47328, 44.094406], [-79.474845, 44.095147], [-79.476596, 44.095509], [-79.47748, 44.097214], [-79.481909, 44.096944], [-79.485332, 44.096184], [-79.48926, 44.095648], [-79.490539, 44.097626], [-79.491401, 44.101178], [-79.492225, 44.104226], [-79.492458, 44.10541], [-79.492094, 44.109966], [-79.492816, 44.113506], [-79.49365, 44.116918], [-79.494544, 44.120328], [-79.495662, 44.125342], [-79.49629, 44.12799], [-79.498267, 44.12792]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_c336cf023a3176247bd1b6098ed3ac6f.bindTooltip(
                `<div>
                     52 HOLLAND LANDING
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_c336cf023a3176247bd1b6098ed3ac6f.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_e0480f08fb8e46e1d95d74296f84c641_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A54686", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_e0480f08fb8e46e1d95d74296f84c641_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_e0480f08fb8e46e1d95d74296f84c641 = L.geoJson(null, {
                onEachFeature: geo_json_e0480f08fb8e46e1d95d74296f84c641_onEachFeature,
            
                style: geo_json_e0480f08fb8e46e1d95d74296f84c641_styler,
            ...{
}
        });

        function geo_json_e0480f08fb8e46e1d95d74296f84c641_add (data) {
            geo_json_e0480f08fb8e46e1d95d74296f84c641
                .addData(data);
        }
            geo_json_e0480f08fb8e46e1d95d74296f84c641_add({"features": [{"geometry": {"coordinates": [[-79.498267, 44.12792], [-79.506972, 44.126059], [-79.508734, 44.125152], [-79.511199, 44.120446], [-79.510109, 44.116463], [-79.508328, 44.109775], [-79.50758, 44.106861], [-79.505528, 44.10649], [-79.504658, 44.103292], [-79.497508, 44.100307], [-79.491829, 44.101339], [-79.490753, 44.097778], [-79.486483, 44.095834], [-79.482223, 44.096726], [-79.47798, 44.097649], [-79.474087, 44.098303], [-79.47328, 44.094406], [-79.474845, 44.095147], [-79.476596, 44.095509], [-79.47748, 44.097214], [-79.481909, 44.096944], [-79.485332, 44.096184], [-79.48926, 44.095648], [-79.487469, 44.083053], [-79.486007, 44.077242], [-79.485036, 44.073095], [-79.484559, 44.071102], [-79.483827, 44.068092], [-79.483455, 44.066601], [-79.482941, 44.064597], [-79.482177, 44.061349], [-79.486477, 44.05839], [-79.48617, 44.054512], [-79.487077, 44.053076]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_e0480f08fb8e46e1d95d74296f84c641.bindTooltip(
                `<div>
                     52 HOLLAND LANDING
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_e0480f08fb8e46e1d95d74296f84c641.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_78b0f7ad2e87d38e50e7760da7b8ecd3_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A54686", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_78b0f7ad2e87d38e50e7760da7b8ecd3_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_78b0f7ad2e87d38e50e7760da7b8ecd3 = L.geoJson(null, {
                onEachFeature: geo_json_78b0f7ad2e87d38e50e7760da7b8ecd3_onEachFeature,
            
                style: geo_json_78b0f7ad2e87d38e50e7760da7b8ecd3_styler,
            ...{
}
        });

        function geo_json_78b0f7ad2e87d38e50e7760da7b8ecd3_add (data) {
            geo_json_78b0f7ad2e87d38e50e7760da7b8ecd3
                .addData(data);
        }
            geo_json_78b0f7ad2e87d38e50e7760da7b8ecd3_add({"features": [{"geometry": {"coordinates": [[-79.498267, 44.12792], [-79.506972, 44.126059], [-79.508734, 44.125152], [-79.511199, 44.120446], [-79.510109, 44.116463], [-79.508328, 44.109775], [-79.50758, 44.106861], [-79.505528, 44.10649], [-79.504658, 44.103292], [-79.497508, 44.100307], [-79.491829, 44.101339], [-79.490753, 44.097778], [-79.487469, 44.083053], [-79.486007, 44.077242], [-79.485036, 44.073095], [-79.484559, 44.071102], [-79.483827, 44.068092], [-79.483455, 44.066601], [-79.482941, 44.064597], [-79.482177, 44.061349], [-79.486477, 44.05839], [-79.48617, 44.054512], [-79.487077, 44.053076]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_78b0f7ad2e87d38e50e7760da7b8ecd3.bindTooltip(
                `<div>
                     52 HOLLAND LANDING
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_78b0f7ad2e87d38e50e7760da7b8ecd3.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_e7baf3a999bc6f60982e06e876bc7937_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#806A50", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_e7baf3a999bc6f60982e06e876bc7937_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_e7baf3a999bc6f60982e06e876bc7937 = L.geoJson(null, {
                onEachFeature: geo_json_e7baf3a999bc6f60982e06e876bc7937_onEachFeature,
            
                style: geo_json_e7baf3a999bc6f60982e06e876bc7937_styler,
            ...{
}
        });

        function geo_json_e7baf3a999bc6f60982e06e876bc7937_add (data) {
            geo_json_e7baf3a999bc6f60982e06e876bc7937
                .addData(data);
        }
            geo_json_e7baf3a999bc6f60982e06e876bc7937_add({"features": [{"geometry": {"coordinates": [[-79.465904, 43.999965], [-79.464299, 44.000311], [-79.460693, 44.001138], [-79.456992, 44.001909], [-79.451138, 44.003193], [-79.444124, 44.007131], [-79.44457, 44.009259], [-79.445307, 44.012534], [-79.445931, 44.01537], [-79.446733, 44.018976], [-79.447252, 44.021163], [-79.447708, 44.023449], [-79.448108, 44.025081], [-79.449047, 44.029116], [-79.44999, 44.033276], [-79.450571, 44.035987], [-79.451097, 44.038292], [-79.451772, 44.041027], [-79.452388, 44.043426], [-79.453192, 44.04677], [-79.452896, 44.049378], [-79.454926, 44.051653], [-79.457136, 44.053066], [-79.459367, 44.056068], [-79.46096, 44.05896], [-79.462242, 44.061675], [-79.463102, 44.063907], [-79.459733, 44.067652], [-79.459095, 44.0698], [-79.458835, 44.072564], [-79.459121, 44.073605], [-79.456474, 44.078486]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_e7baf3a999bc6f60982e06e876bc7937.bindTooltip(
                `<div>
                     54 BAYVIEW
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_e7baf3a999bc6f60982e06e876bc7937.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_be2dd6f6cc62b65ab57861b04a2fc438_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#806A50", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_be2dd6f6cc62b65ab57861b04a2fc438_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_be2dd6f6cc62b65ab57861b04a2fc438 = L.geoJson(null, {
                onEachFeature: geo_json_be2dd6f6cc62b65ab57861b04a2fc438_onEachFeature,
            
                style: geo_json_be2dd6f6cc62b65ab57861b04a2fc438_styler,
            ...{
}
        });

        function geo_json_be2dd6f6cc62b65ab57861b04a2fc438_add (data) {
            geo_json_be2dd6f6cc62b65ab57861b04a2fc438
                .addData(data);
        }
            geo_json_be2dd6f6cc62b65ab57861b04a2fc438_add({"features": [{"geometry": {"coordinates": [[-79.456474, 44.078486], [-79.459318, 44.073858], [-79.45909, 44.070083], [-79.459931, 44.068101], [-79.462935, 44.064472], [-79.462556, 44.062077], [-79.46145, 44.05948], [-79.460903, 44.058284], [-79.459746, 44.056296], [-79.457357, 44.053179], [-79.454794, 44.051511], [-79.453002, 44.049624], [-79.45343, 44.047013], [-79.452594, 44.043727], [-79.452143, 44.041401], [-79.451477, 44.038668], [-79.450997, 44.03634], [-79.450406, 44.033668], [-79.449452, 44.029585], [-79.448687, 44.026176], [-79.448128, 44.023681], [-79.44763, 44.021546], [-79.447196, 44.019485], [-79.446371, 44.015695], [-79.445712, 44.012977], [-79.445006, 44.009733], [-79.444519, 44.007426], [-79.444088, 44.005366], [-79.444889, 44.004867], [-79.450674, 44.003497], [-79.452112, 44.003147], [-79.454002, 44.002749], [-79.457317, 44.002018], [-79.460502, 44.001278], [-79.463921, 44.000489], [-79.465688, 43.999731], [-79.465153, 43.99718], [-79.466688, 43.996796], [-79.465904, 43.999965]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_be2dd6f6cc62b65ab57861b04a2fc438.bindTooltip(
                `<div>
                     54 BAYVIEW
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_be2dd6f6cc62b65ab57861b04a2fc438.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_fa42c8a87451908add892f9fee043fd3_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0058A9", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_fa42c8a87451908add892f9fee043fd3_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_fa42c8a87451908add892f9fee043fd3 = L.geoJson(null, {
                onEachFeature: geo_json_fa42c8a87451908add892f9fee043fd3_onEachFeature,
            
                style: geo_json_fa42c8a87451908add892f9fee043fd3_styler,
            ...{
}
        });

        function geo_json_fa42c8a87451908add892f9fee043fd3_add (data) {
            geo_json_fa42c8a87451908add892f9fee043fd3
                .addData(data);
        }
            geo_json_fa42c8a87451908add892f9fee043fd3_add({"features": [{"geometry": {"coordinates": [[-79.487097, 44.052926], [-79.485781, 44.053567], [-79.483007, 44.054155], [-79.48074, 44.054598], [-79.478129, 44.055201], [-79.474817, 44.055928], [-79.472341, 44.05651], [-79.468047, 44.057485], [-79.465736, 44.057986], [-79.463903, 44.058407], [-79.461437, 44.058931], [-79.458961, 44.059392], [-79.455828, 44.060245], [-79.454515, 44.06049], [-79.452712, 44.060904], [-79.449566, 44.061604], [-79.445043, 44.063472], [-79.445766, 44.066696], [-79.444236, 44.068049], [-79.442456, 44.070143], [-79.442438, 44.071534], [-79.44497, 44.071677], [-79.449969, 44.071992], [-79.452897, 44.072277], [-79.451638, 44.073626], [-79.447048, 44.075023], [-79.445522, 44.077554], [-79.441431, 44.077424], [-79.437942, 44.078824], [-79.435746, 44.079569], [-79.43482, 44.076712], [-79.434061, 44.07379], [-79.433443, 44.071444], [-79.433106, 44.070004], [-79.430636, 44.067671], [-79.426599, 44.066878], [-79.421106, 44.06736]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_fa42c8a87451908add892f9fee043fd3.bindTooltip(
                `<div>
                     55 DAVIS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_fa42c8a87451908add892f9fee043fd3.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_b1dd0fd3af0526767639417e5c2b3c4f_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0058A9", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_b1dd0fd3af0526767639417e5c2b3c4f_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_b1dd0fd3af0526767639417e5c2b3c4f = L.geoJson(null, {
                onEachFeature: geo_json_b1dd0fd3af0526767639417e5c2b3c4f_onEachFeature,
            
                style: geo_json_b1dd0fd3af0526767639417e5c2b3c4f_styler,
            ...{
}
        });

        function geo_json_b1dd0fd3af0526767639417e5c2b3c4f_add (data) {
            geo_json_b1dd0fd3af0526767639417e5c2b3c4f
                .addData(data);
        }
            geo_json_b1dd0fd3af0526767639417e5c2b3c4f_add({"features": [{"geometry": {"coordinates": [[-79.421106, 44.06736], [-79.426071, 44.067266], [-79.429516, 44.066488], [-79.431627, 44.066012], [-79.431973, 44.06657], [-79.430636, 44.067671], [-79.431627, 44.066012], [-79.431973, 44.06657], [-79.432338, 44.067728], [-79.432716, 44.069652], [-79.433685, 44.073449], [-79.434373, 44.076295], [-79.43615, 44.079595], [-79.437872, 44.079049], [-79.440326, 44.077407], [-79.445177, 44.07772], [-79.447197, 44.075189], [-79.451432, 44.073753], [-79.452129, 44.07203], [-79.449235, 44.071939], [-79.445144, 44.071613], [-79.442653, 44.071567], [-79.442869, 44.069799], [-79.444239, 44.068168], [-79.44578, 44.066908], [-79.445046, 44.063053], [-79.445579, 44.062777], [-79.449215, 44.061995], [-79.45184, 44.061384], [-79.454082, 44.060876], [-79.456139, 44.060444], [-79.459338, 44.05966], [-79.461761, 44.059179], [-79.463488, 44.058764], [-79.465752, 44.05828], [-79.467995, 44.05774], [-79.47188, 44.056898], [-79.474401, 44.056351], [-79.477758, 44.055598], [-79.479985, 44.055123], [-79.483716, 44.054279], [-79.487097, 44.052926]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_b1dd0fd3af0526767639417e5c2b3c4f.bindTooltip(
                `<div>
                     55 DAVIS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_b1dd0fd3af0526767639417e5c2b3c4f.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_e5a3d70ab4a51724f0e78bb89388b059_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#FBB034", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_e5a3d70ab4a51724f0e78bb89388b059_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_e5a3d70ab4a51724f0e78bb89388b059 = L.geoJson(null, {
                onEachFeature: geo_json_e5a3d70ab4a51724f0e78bb89388b059_onEachFeature,
            
                style: geo_json_e5a3d70ab4a51724f0e78bb89388b059_styler,
            ...{
}
        });

        function geo_json_e5a3d70ab4a51724f0e78bb89388b059_add (data) {
            geo_json_e5a3d70ab4a51724f0e78bb89388b059
                .addData(data);
        }
            geo_json_e5a3d70ab4a51724f0e78bb89388b059_add({"features": [{"geometry": {"coordinates": [[-79.486885, 44.052838], [-79.48617, 44.054512], [-79.484808, 44.051979], [-79.48463, 44.050258], [-79.484776, 44.048387], [-79.484382, 44.046147], [-79.482819, 44.04479], [-79.47988, 44.044995], [-79.478417, 44.045301], [-79.476463, 44.04578], [-79.47411, 44.046291], [-79.47154, 44.0468], [-79.469916, 44.047199], [-79.467211, 44.047803], [-79.463001, 44.048724], [-79.460196, 44.049339], [-79.457251, 44.050028], [-79.454794, 44.051511], [-79.450597, 44.051994], [-79.445975, 44.053067], [-79.441149, 44.054156], [-79.435641, 44.055437], [-79.432834, 44.056041], [-79.429899, 44.05672], [-79.427788, 44.057223], [-79.424551, 44.058093], [-79.421162, 44.05885], [-79.422234, 44.061345], [-79.425047, 44.064333], [-79.425903, 44.066276], [-79.429516, 44.066488], [-79.431627, 44.066012], [-79.431973, 44.06657], [-79.430636, 44.067671]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_e5a3d70ab4a51724f0e78bb89388b059.bindTooltip(
                `<div>
                     56 GORHAM - EAGLE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_e5a3d70ab4a51724f0e78bb89388b059.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_9b6cb41b5b3f651e0258b0aced993eae_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#FBB034", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_9b6cb41b5b3f651e0258b0aced993eae_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_9b6cb41b5b3f651e0258b0aced993eae = L.geoJson(null, {
                onEachFeature: geo_json_9b6cb41b5b3f651e0258b0aced993eae_onEachFeature,
            
                style: geo_json_9b6cb41b5b3f651e0258b0aced993eae_styler,
            ...{
}
        });

        function geo_json_9b6cb41b5b3f651e0258b0aced993eae_add (data) {
            geo_json_9b6cb41b5b3f651e0258b0aced993eae
                .addData(data);
        }
            geo_json_9b6cb41b5b3f651e0258b0aced993eae_add({"features": [{"geometry": {"coordinates": [[-79.486885, 44.052838], [-79.484808, 44.051979], [-79.48463, 44.050258], [-79.484776, 44.048387], [-79.484382, 44.046147], [-79.482819, 44.04479], [-79.47988, 44.044995], [-79.478417, 44.045301], [-79.476463, 44.04578], [-79.47411, 44.046291], [-79.47154, 44.0468], [-79.469916, 44.047199], [-79.467211, 44.047803], [-79.463001, 44.048724], [-79.460196, 44.049339], [-79.457251, 44.050028], [-79.454794, 44.051511], [-79.450597, 44.051994], [-79.445975, 44.053067], [-79.441149, 44.054156], [-79.435641, 44.055437], [-79.432834, 44.056041], [-79.429899, 44.05672], [-79.427788, 44.057223], [-79.424551, 44.058093], [-79.421162, 44.05885], [-79.422234, 44.061345], [-79.425047, 44.064333], [-79.425903, 44.066276], [-79.429516, 44.066488], [-79.431627, 44.066012], [-79.431973, 44.06657], [-79.430636, 44.067671]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_9b6cb41b5b3f651e0258b0aced993eae.bindTooltip(
                `<div>
                     56 GORHAM - EAGLE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_9b6cb41b5b3f651e0258b0aced993eae.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_adf346da68d7331350da24d4e5236d3a_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#FBB034", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_adf346da68d7331350da24d4e5236d3a_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_adf346da68d7331350da24d4e5236d3a = L.geoJson(null, {
                onEachFeature: geo_json_adf346da68d7331350da24d4e5236d3a_onEachFeature,
            
                style: geo_json_adf346da68d7331350da24d4e5236d3a_styler,
            ...{
}
        });

        function geo_json_adf346da68d7331350da24d4e5236d3a_add (data) {
            geo_json_adf346da68d7331350da24d4e5236d3a
                .addData(data);
        }
            geo_json_adf346da68d7331350da24d4e5236d3a_add({"features": [{"geometry": {"coordinates": [[-79.430636, 44.067671], [-79.431627, 44.066012], [-79.431973, 44.06657], [-79.432338, 44.067728], [-79.432716, 44.069652], [-79.433685, 44.073449], [-79.434373, 44.076295], [-79.43522, 44.079483], [-79.431108, 44.080513], [-79.427836, 44.081254], [-79.426978, 44.079671], [-79.426254, 44.077135], [-79.425575, 44.073997], [-79.425317, 44.070755], [-79.426313, 44.069581], [-79.426543, 44.067269], [-79.429516, 44.066488], [-79.431627, 44.066012], [-79.431973, 44.06657], [-79.430636, 44.067671], [-79.426599, 44.066878], [-79.42542, 44.064696], [-79.422273, 44.061213], [-79.421036, 44.059169], [-79.424518, 44.05824], [-79.427316, 44.057436], [-79.429251, 44.05704], [-79.432287, 44.056323], [-79.435311, 44.055649], [-79.441474, 44.054233], [-79.444792, 44.053445], [-79.450817, 44.052042], [-79.453016, 44.051621], [-79.454926, 44.051653], [-79.45783, 44.049991], [-79.460376, 44.049414], [-79.462544, 44.048936], [-79.467013, 44.047952], [-79.46923, 44.047462], [-79.471111, 44.047027], [-79.47375, 44.046469], [-79.47615, 44.045942], [-79.4792, 44.045301], [-79.482157, 44.044815], [-79.484305, 44.046441], [-79.484627, 44.048227], [-79.484517, 44.049968], [-79.484547, 44.051922], [-79.486885, 44.052838]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_adf346da68d7331350da24d4e5236d3a.bindTooltip(
                `<div>
                     56 GORHAM - EAGLE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_adf346da68d7331350da24d4e5236d3a.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_c3efe9c6913db8d48330f5e365e932e0_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00AEEF", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_c3efe9c6913db8d48330f5e365e932e0_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_c3efe9c6913db8d48330f5e365e932e0 = L.geoJson(null, {
                onEachFeature: geo_json_c3efe9c6913db8d48330f5e365e932e0_onEachFeature,
            
                style: geo_json_c3efe9c6913db8d48330f5e365e932e0_styler,
            ...{
}
        });

        function geo_json_c3efe9c6913db8d48330f5e365e932e0_add (data) {
            geo_json_c3efe9c6913db8d48330f5e365e932e0
                .addData(data);
        }
            geo_json_c3efe9c6913db8d48330f5e365e932e0_add({"features": [{"geometry": {"coordinates": [[-79.486929, 44.053065], [-79.490529, 44.052823], [-79.494287, 44.049601], [-79.491923, 44.048508], [-79.490572, 44.046084], [-79.492695, 44.044809], [-79.498982, 44.044686], [-79.502032, 44.045717], [-79.504314, 44.045597], [-79.501475, 44.038827], [-79.497084, 44.035591], [-79.49471, 44.036146], [-79.491142, 44.036703], [-79.487338, 44.037712], [-79.485033, 44.038568], [-79.483367, 44.036498], [-79.481753, 44.034889], [-79.476288, 44.036089], [-79.474977, 44.036404], [-79.469275, 44.037693], [-79.464527, 44.038766], [-79.458145, 44.040187], [-79.454931, 44.040843], [-79.452288, 44.041066], [-79.449653, 44.041436], [-79.446665, 44.042756], [-79.438148, 44.044954], [-79.427388, 44.048048], [-79.427723, 44.04973], [-79.428145, 44.051404], [-79.428779, 44.053827], [-79.429725, 44.057667], [-79.430263, 44.059913], [-79.431174, 44.063293], [-79.431973, 44.06657], [-79.430636, 44.067671]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_c3efe9c6913db8d48330f5e365e932e0.bindTooltip(
                `<div>
                     57 MULOCK
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_c3efe9c6913db8d48330f5e365e932e0.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_8b329b8a37c1b6a0766d4a9c303e9581_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00AEEF", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_8b329b8a37c1b6a0766d4a9c303e9581_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_8b329b8a37c1b6a0766d4a9c303e9581 = L.geoJson(null, {
                onEachFeature: geo_json_8b329b8a37c1b6a0766d4a9c303e9581_onEachFeature,
            
                style: geo_json_8b329b8a37c1b6a0766d4a9c303e9581_styler,
            ...{
}
        });

        function geo_json_8b329b8a37c1b6a0766d4a9c303e9581_add (data) {
            geo_json_8b329b8a37c1b6a0766d4a9c303e9581
                .addData(data);
        }
            geo_json_8b329b8a37c1b6a0766d4a9c303e9581_add({"features": [{"geometry": {"coordinates": [[-79.430636, 44.067671], [-79.431481, 44.063383], [-79.43072, 44.060306], [-79.429811, 44.056968], [-79.429154, 44.054135], [-79.428492, 44.051663], [-79.428066, 44.049958], [-79.427646, 44.047688], [-79.428753, 44.047287], [-79.434646, 44.04598], [-79.437716, 44.045312], [-79.446418, 44.043226], [-79.451657, 44.041408], [-79.454534, 44.041183], [-79.458408, 44.040335], [-79.463762, 44.039164], [-79.468974, 44.038027], [-79.475563, 44.036497], [-79.482342, 44.035022], [-79.483159, 44.036269], [-79.484794, 44.038615], [-79.487725, 44.037613], [-79.490749, 44.036781], [-79.494481, 44.036283], [-79.497105, 44.035776], [-79.500745, 44.038542], [-79.505057, 44.045108], [-79.502285, 44.045768], [-79.499299, 44.044684], [-79.4929, 44.044649], [-79.490103, 44.04614], [-79.491564, 44.04858], [-79.493972, 44.049537], [-79.49602, 44.050623], [-79.491139, 44.052399], [-79.486929, 44.053065]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_8b329b8a37c1b6a0766d4a9c303e9581.bindTooltip(
                `<div>
                     57 MULOCK
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_8b329b8a37c1b6a0766d4a9c303e9581.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_3b8984916ab2df6cbcb6b6eab6ee44fc_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00AEEF", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_3b8984916ab2df6cbcb6b6eab6ee44fc_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_3b8984916ab2df6cbcb6b6eab6ee44fc = L.geoJson(null, {
                onEachFeature: geo_json_3b8984916ab2df6cbcb6b6eab6ee44fc_onEachFeature,
            
                style: geo_json_3b8984916ab2df6cbcb6b6eab6ee44fc_styler,
            ...{
}
        });

        function geo_json_3b8984916ab2df6cbcb6b6eab6ee44fc_add (data) {
            geo_json_3b8984916ab2df6cbcb6b6eab6ee44fc
                .addData(data);
        }
            geo_json_3b8984916ab2df6cbcb6b6eab6ee44fc_add({"features": [{"geometry": {"coordinates": [[-79.626181, 43.773322], [-79.619176, 43.773496], [-79.613178, 43.774917], [-79.608653, 43.775925], [-79.605681, 43.77661], [-79.597505, 43.778488], [-79.589548, 43.78047], [-79.583721, 43.781775], [-79.579982, 43.782506], [-79.57345, 43.783899], [-79.567006, 43.785227], [-79.556476, 43.787427], [-79.552058, 43.788354], [-79.547894, 43.789081], [-79.533889, 43.791977], [-79.531206, 43.792435], [-79.527354, 43.793284], [-79.524773, 43.793804], [-79.521469, 43.794667], [-79.518061, 43.795416], [-79.515118, 43.796163], [-79.499674, 43.799959], [-79.490613, 43.802164], [-79.482493, 43.805852], [-79.475051, 43.805362], [-79.469121, 43.806677], [-79.464577, 43.807642], [-79.461283, 43.808389], [-79.457557, 43.809223], [-79.454219, 43.809682], [-79.455437, 43.806182], [-79.457123, 43.801771], [-79.454098, 43.802232], [-79.451552, 43.802786], [-79.447408, 43.80359], [-79.445075, 43.804005], [-79.440044, 43.804899], [-79.437017, 43.805531], [-79.433292, 43.806408], [-79.427322, 43.806892], [-79.422827, 43.806933], [-79.422211, 43.805597], [-79.4213, 43.802036], [-79.420274, 43.798244], [-79.420037, 43.797434], [-79.419718, 43.796088], [-79.419191, 43.793992], [-79.418625, 43.791289], [-79.418069, 43.789452], [-79.417496, 43.7872], [-79.415299, 43.78234]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_3b8984916ab2df6cbcb6b6eab6ee44fc.bindTooltip(
                `<div>
                     77 HIGHWAY 7
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_3b8984916ab2df6cbcb6b6eab6ee44fc.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_9c415528c587fdcba3877ad88509dc53_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00AEEF", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_9c415528c587fdcba3877ad88509dc53_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_9c415528c587fdcba3877ad88509dc53 = L.geoJson(null, {
                onEachFeature: geo_json_9c415528c587fdcba3877ad88509dc53_onEachFeature,
            
                style: geo_json_9c415528c587fdcba3877ad88509dc53_styler,
            ...{
}
        });

        function geo_json_9c415528c587fdcba3877ad88509dc53_add (data) {
            geo_json_9c415528c587fdcba3877ad88509dc53
                .addData(data);
        }
            geo_json_9c415528c587fdcba3877ad88509dc53_add({"features": [{"geometry": {"coordinates": [[-79.415299, 43.78234], [-79.416698, 43.78496], [-79.417335, 43.787532], [-79.417977, 43.790138], [-79.418316, 43.79149], [-79.418994, 43.794272], [-79.42011, 43.798695], [-79.420878, 43.801684], [-79.421756, 43.805238], [-79.423692, 43.806919], [-79.426676, 43.806887], [-79.432699, 43.806692], [-79.437772, 43.805606], [-79.440512, 43.805047], [-79.444741, 43.804204], [-79.449365, 43.803492], [-79.451124, 43.803107], [-79.454968, 43.802215], [-79.457324, 43.802068], [-79.456021, 43.805895], [-79.454388, 43.809634], [-79.457067, 43.809698], [-79.460624, 43.808844], [-79.464081, 43.808044], [-79.468684, 43.807055], [-79.474037, 43.805912], [-79.482931, 43.805744], [-79.490286, 43.802496], [-79.499136, 43.800579], [-79.51758, 43.795965], [-79.521061, 43.795117], [-79.524229, 43.794411], [-79.527575, 43.793673], [-79.530799, 43.792984], [-79.533273, 43.792445], [-79.547133, 43.789655], [-79.551476, 43.788788], [-79.555847, 43.787909], [-79.566404, 43.78572], [-79.572781, 43.784417], [-79.579416, 43.782993], [-79.584121, 43.781858], [-79.590232, 43.780547], [-79.597043, 43.778903], [-79.605191, 43.776957], [-79.608975, 43.776164], [-79.612731, 43.775279], [-79.620722, 43.773496], [-79.625159, 43.772458], [-79.64099, 43.768841], [-79.64717, 43.76757], [-79.650031, 43.767051], [-79.655959, 43.76685], [-79.659289, 43.769432], [-79.65732, 43.771251], [-79.653067, 43.773453], [-79.648569, 43.774457], [-79.644212, 43.774954], [-79.639267, 43.775517], [-79.631194, 43.77664], [-79.626968, 43.776793], [-79.626318, 43.774255], [-79.626181, 43.773322]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_9c415528c587fdcba3877ad88509dc53.bindTooltip(
                `<div>
                     77 HIGHWAY 7
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_9c415528c587fdcba3877ad88509dc53.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_a4b08571c93a0e0ff78448fe4419407a_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00AEEF", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_a4b08571c93a0e0ff78448fe4419407a_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_a4b08571c93a0e0ff78448fe4419407a = L.geoJson(null, {
                onEachFeature: geo_json_a4b08571c93a0e0ff78448fe4419407a_onEachFeature,
            
                style: geo_json_a4b08571c93a0e0ff78448fe4419407a_styler,
            ...{
}
        });

        function geo_json_a4b08571c93a0e0ff78448fe4419407a_add (data) {
            geo_json_a4b08571c93a0e0ff78448fe4419407a
                .addData(data);
        }
            geo_json_a4b08571c93a0e0ff78448fe4419407a_add({"features": [{"geometry": {"coordinates": [[-79.454388, 43.809634], [-79.457067, 43.809698], [-79.460624, 43.808844], [-79.464081, 43.808044], [-79.468684, 43.807055], [-79.474037, 43.805912], [-79.482931, 43.805744], [-79.490286, 43.802496], [-79.499136, 43.800579], [-79.51758, 43.795965], [-79.521061, 43.795117], [-79.524229, 43.794411], [-79.527575, 43.793673], [-79.530799, 43.792984], [-79.533273, 43.792445], [-79.547133, 43.789655], [-79.551476, 43.788788], [-79.555847, 43.787909], [-79.566404, 43.78572], [-79.572781, 43.784417], [-79.579416, 43.782993], [-79.584121, 43.781858], [-79.590232, 43.780547], [-79.597043, 43.778903], [-79.605191, 43.776957], [-79.608975, 43.776164], [-79.612731, 43.775279], [-79.620722, 43.773496], [-79.625159, 43.772458], [-79.64099, 43.768841], [-79.64717, 43.76757], [-79.650031, 43.767051], [-79.655959, 43.76685], [-79.659289, 43.769432], [-79.65732, 43.771251], [-79.653067, 43.773453], [-79.648569, 43.774457], [-79.644212, 43.774954], [-79.639267, 43.775517], [-79.631194, 43.77664], [-79.626968, 43.776793], [-79.626318, 43.774255], [-79.626181, 43.773322]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_a4b08571c93a0e0ff78448fe4419407a.bindTooltip(
                `<div>
                     77 HIGHWAY 7
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_a4b08571c93a0e0ff78448fe4419407a.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_866102c83404f0a04f435696bad0ac4b_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00AEEF", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_866102c83404f0a04f435696bad0ac4b_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_866102c83404f0a04f435696bad0ac4b = L.geoJson(null, {
                onEachFeature: geo_json_866102c83404f0a04f435696bad0ac4b_onEachFeature,
            
                style: geo_json_866102c83404f0a04f435696bad0ac4b_styler,
            ...{
}
        });

        function geo_json_866102c83404f0a04f435696bad0ac4b_add (data) {
            geo_json_866102c83404f0a04f435696bad0ac4b
                .addData(data);
        }
            geo_json_866102c83404f0a04f435696bad0ac4b_add({"features": [{"geometry": {"coordinates": [[-79.490613, 43.802164], [-79.482493, 43.805852], [-79.475051, 43.805362], [-79.469121, 43.806677], [-79.464577, 43.807642], [-79.461283, 43.808389], [-79.457557, 43.809223], [-79.454219, 43.809682], [-79.45023, 43.810619], [-79.443685, 43.812106], [-79.438628, 43.813223], [-79.436276, 43.813747], [-79.432606, 43.814526], [-79.427575, 43.815604], [-79.425221, 43.816138], [-79.424259, 43.814736], [-79.423491, 43.811126], [-79.422566, 43.807246], [-79.422211, 43.805597], [-79.4213, 43.802036], [-79.420274, 43.798244], [-79.420037, 43.797434], [-79.419718, 43.796088], [-79.419191, 43.793992], [-79.418625, 43.791289], [-79.418069, 43.789452], [-79.417496, 43.7872], [-79.415299, 43.78234]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_866102c83404f0a04f435696bad0ac4b.bindTooltip(
                `<div>
                     77 HIGHWAY 7
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_866102c83404f0a04f435696bad0ac4b.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_b386ae5dcfa8119f7d99c2bad9ed5877_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00AEEF", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_b386ae5dcfa8119f7d99c2bad9ed5877_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_b386ae5dcfa8119f7d99c2bad9ed5877 = L.geoJson(null, {
                onEachFeature: geo_json_b386ae5dcfa8119f7d99c2bad9ed5877_onEachFeature,
            
                style: geo_json_b386ae5dcfa8119f7d99c2bad9ed5877_styler,
            ...{
}
        });

        function geo_json_b386ae5dcfa8119f7d99c2bad9ed5877_add (data) {
            geo_json_b386ae5dcfa8119f7d99c2bad9ed5877
                .addData(data);
        }
            geo_json_b386ae5dcfa8119f7d99c2bad9ed5877_add({"features": [{"geometry": {"coordinates": [[-79.626181, 43.773322], [-79.619176, 43.773496], [-79.613178, 43.774917], [-79.608653, 43.775925], [-79.605681, 43.77661], [-79.597505, 43.778488], [-79.589548, 43.78047], [-79.583721, 43.781775], [-79.579982, 43.782506], [-79.57345, 43.783899], [-79.567006, 43.785227], [-79.556476, 43.787427], [-79.552058, 43.788354], [-79.547894, 43.789081], [-79.533889, 43.791977], [-79.531206, 43.792435], [-79.527354, 43.793284], [-79.524773, 43.793804], [-79.521469, 43.794667], [-79.518061, 43.795416], [-79.515118, 43.796163], [-79.499674, 43.799959], [-79.490613, 43.802164], [-79.482493, 43.805852], [-79.475051, 43.805362], [-79.469121, 43.806677], [-79.464577, 43.807642], [-79.461283, 43.808389], [-79.457557, 43.809223], [-79.454219, 43.809682], [-79.45023, 43.810619], [-79.443685, 43.812106], [-79.438628, 43.813223], [-79.436276, 43.813747], [-79.432606, 43.814526], [-79.427575, 43.815604], [-79.425221, 43.816138], [-79.424259, 43.814736], [-79.423491, 43.811126], [-79.422566, 43.807246], [-79.422211, 43.805597], [-79.4213, 43.802036], [-79.420274, 43.798244], [-79.420037, 43.797434], [-79.419718, 43.796088], [-79.419191, 43.793992], [-79.418625, 43.791289], [-79.418069, 43.789452], [-79.417496, 43.7872], [-79.415299, 43.78234]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_b386ae5dcfa8119f7d99c2bad9ed5877.bindTooltip(
                `<div>
                     77 HIGHWAY 7
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_b386ae5dcfa8119f7d99c2bad9ed5877.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_af2ab26e58cd2ac3d5ff32b7b4b16146_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00AEEF", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_af2ab26e58cd2ac3d5ff32b7b4b16146_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_af2ab26e58cd2ac3d5ff32b7b4b16146 = L.geoJson(null, {
                onEachFeature: geo_json_af2ab26e58cd2ac3d5ff32b7b4b16146_onEachFeature,
            
                style: geo_json_af2ab26e58cd2ac3d5ff32b7b4b16146_styler,
            ...{
}
        });

        function geo_json_af2ab26e58cd2ac3d5ff32b7b4b16146_add (data) {
            geo_json_af2ab26e58cd2ac3d5ff32b7b4b16146
                .addData(data);
        }
            geo_json_af2ab26e58cd2ac3d5ff32b7b4b16146_add({"features": [{"geometry": {"coordinates": [[-79.415299, 43.78234], [-79.416698, 43.78496], [-79.417335, 43.787532], [-79.417977, 43.790138], [-79.418316, 43.79149], [-79.418994, 43.794272], [-79.42011, 43.798695], [-79.420878, 43.801684], [-79.421756, 43.805238], [-79.422192, 43.807001], [-79.423127, 43.810912], [-79.42381, 43.814029], [-79.425194, 43.816249], [-79.428161, 43.815589], [-79.432384, 43.81469], [-79.435924, 43.813938], [-79.438198, 43.813455], [-79.4428, 43.81248], [-79.449522, 43.811062], [-79.454388, 43.809634], [-79.457067, 43.809698], [-79.460624, 43.808844], [-79.464081, 43.808044], [-79.468684, 43.807055], [-79.474037, 43.805912], [-79.482931, 43.805744], [-79.490286, 43.802496], [-79.499136, 43.800579], [-79.51758, 43.795965], [-79.521061, 43.795117], [-79.524229, 43.794411], [-79.527575, 43.793673], [-79.530799, 43.792984], [-79.533273, 43.792445], [-79.547133, 43.789655], [-79.551476, 43.788788], [-79.555847, 43.787909], [-79.566404, 43.78572], [-79.572781, 43.784417], [-79.579416, 43.782993], [-79.584121, 43.781858], [-79.590232, 43.780547], [-79.597043, 43.778903], [-79.605191, 43.776957], [-79.608975, 43.776164], [-79.612731, 43.775279], [-79.620722, 43.773496], [-79.625159, 43.772458], [-79.64099, 43.768841], [-79.64717, 43.76757], [-79.650031, 43.767051], [-79.655959, 43.76685], [-79.659289, 43.769432], [-79.65732, 43.771251], [-79.653067, 43.773453], [-79.648569, 43.774457], [-79.644212, 43.774954], [-79.639267, 43.775517], [-79.631194, 43.77664], [-79.626968, 43.776793], [-79.626318, 43.774255], [-79.626181, 43.773322]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_af2ab26e58cd2ac3d5ff32b7b4b16146.bindTooltip(
                `<div>
                     77 HIGHWAY 7
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_af2ab26e58cd2ac3d5ff32b7b4b16146.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_7eae1751a691c5ef1072bd10e13a7042_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#F37053", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_7eae1751a691c5ef1072bd10e13a7042_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_7eae1751a691c5ef1072bd10e13a7042 = L.geoJson(null, {
                onEachFeature: geo_json_7eae1751a691c5ef1072bd10e13a7042_onEachFeature,
            
                style: geo_json_7eae1751a691c5ef1072bd10e13a7042_styler,
            ...{
}
        });

        function geo_json_7eae1751a691c5ef1072bd10e13a7042_add (data) {
            geo_json_7eae1751a691c5ef1072bd10e13a7042
                .addData(data);
        }
            geo_json_7eae1751a691c5ef1072bd10e13a7042_add({"features": [{"geometry": {"coordinates": [[-79.468666, 43.89286], [-79.468936, 43.894405], [-79.466513, 43.884222], [-79.462686, 43.884967], [-79.460766, 43.885405], [-79.457958, 43.886002], [-79.45251, 43.887152], [-79.448378, 43.888074], [-79.443889, 43.888964], [-79.441911, 43.889389], [-79.438591, 43.890121], [-79.435962, 43.890746], [-79.4315, 43.891677], [-79.427741, 43.892513], [-79.425316, 43.893033], [-79.420096, 43.89353], [-79.413244, 43.894439], [-79.409658, 43.895231], [-79.404685, 43.896339], [-79.401084, 43.897093], [-79.396437, 43.898254], [-79.39256, 43.899314], [-79.378282, 43.902493], [-79.375154, 43.903251], [-79.372092, 43.903953], [-79.37074, 43.899619], [-79.370063, 43.896923], [-79.372906, 43.896763], [-79.376758, 43.896583], [-79.378487, 43.896996]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_7eae1751a691c5ef1072bd10e13a7042.bindTooltip(
                `<div>
                     80 ELGIN MILLS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_7eae1751a691c5ef1072bd10e13a7042.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_e6b7efd7d6a781645934be5ea8f0f539_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#F37053", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_e6b7efd7d6a781645934be5ea8f0f539_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_e6b7efd7d6a781645934be5ea8f0f539 = L.geoJson(null, {
                onEachFeature: geo_json_e6b7efd7d6a781645934be5ea8f0f539_onEachFeature,
            
                style: geo_json_e6b7efd7d6a781645934be5ea8f0f539_styler,
            ...{
}
        });

        function geo_json_e6b7efd7d6a781645934be5ea8f0f539_add (data) {
            geo_json_e6b7efd7d6a781645934be5ea8f0f539
                .addData(data);
        }
            geo_json_e6b7efd7d6a781645934be5ea8f0f539_add({"features": [{"geometry": {"coordinates": [[-79.378487, 43.896996], [-79.377247, 43.899746], [-79.377272, 43.901278], [-79.391956, 43.899651], [-79.395253, 43.898848], [-79.39687, 43.898337], [-79.400402, 43.897487], [-79.404176, 43.896664], [-79.409193, 43.895542], [-79.412728, 43.894768], [-79.41943, 43.893744], [-79.424844, 43.893362], [-79.426859, 43.892915], [-79.430852, 43.892027], [-79.436046, 43.890895], [-79.438204, 43.890483], [-79.4412, 43.889828], [-79.4437, 43.889207], [-79.448611, 43.888168], [-79.452052, 43.887473], [-79.457556, 43.886255], [-79.460382, 43.885606], [-79.463536, 43.884979], [-79.466976, 43.884296], [-79.468179, 43.888451], [-79.468666, 43.89286]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_e6b7efd7d6a781645934be5ea8f0f539.bindTooltip(
                `<div>
                     80 ELGIN MILLS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_e6b7efd7d6a781645934be5ea8f0f539.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_01286239824f6e83f019a83da4aa708c_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#806A50", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_01286239824f6e83f019a83da4aa708c_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_01286239824f6e83f019a83da4aa708c = L.geoJson(null, {
                onEachFeature: geo_json_01286239824f6e83f019a83da4aa708c_onEachFeature,
            
                style: geo_json_01286239824f6e83f019a83da4aa708c_styler,
            ...{
}
        });

        function geo_json_01286239824f6e83f019a83da4aa708c_add (data) {
            geo_json_01286239824f6e83f019a83da4aa708c
                .addData(data);
        }
            geo_json_01286239824f6e83f019a83da4aa708c_add({"features": [{"geometry": {"coordinates": [[-79.441887, 43.89471], [-79.443299, 43.89848], [-79.444081, 43.901573], [-79.444742, 43.904543], [-79.445549, 43.907563], [-79.446548, 43.911482], [-79.447089, 43.913846], [-79.447782, 43.916541], [-79.449992, 43.922505], [-79.455375, 43.921461], [-79.45624, 43.921204], [-79.460666, 43.920277], [-79.466628, 43.918963], [-79.470681, 43.91809], [-79.474282, 43.91729], [-79.472352, 43.91349], [-79.469747, 43.913809], [-79.468202, 43.910365], [-79.467778, 43.906634], [-79.466312, 43.903792], [-79.464415, 43.903747], [-79.460084, 43.90476], [-79.458044, 43.905151], [-79.455247, 43.905749], [-79.452194, 43.907695], [-79.452893, 43.909438], [-79.455718, 43.909866], [-79.459239, 43.911111], [-79.460927, 43.913656], [-79.456688, 43.914955], [-79.451411, 43.914303], [-79.447832, 43.913892], [-79.446945, 43.911874], [-79.446084, 43.908107], [-79.445298, 43.90495], [-79.444488, 43.901299], [-79.443908, 43.898838], [-79.441887, 43.89471]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_01286239824f6e83f019a83da4aa708c.bindTooltip(
                `<div>
                     81 INSPIRATION
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_01286239824f6e83f019a83da4aa708c.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_0e58e5992e07e08eb5be115d552f40fc_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#806A50", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_0e58e5992e07e08eb5be115d552f40fc_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_0e58e5992e07e08eb5be115d552f40fc = L.geoJson(null, {
                onEachFeature: geo_json_0e58e5992e07e08eb5be115d552f40fc_onEachFeature,
            
                style: geo_json_0e58e5992e07e08eb5be115d552f40fc_styler,
            ...{
}
        });

        function geo_json_0e58e5992e07e08eb5be115d552f40fc_add (data) {
            geo_json_0e58e5992e07e08eb5be115d552f40fc
                .addData(data);
        }
            geo_json_0e58e5992e07e08eb5be115d552f40fc_add({"features": [{"geometry": {"coordinates": [[-79.441887, 43.89471], [-79.443299, 43.89848], [-79.444081, 43.901573], [-79.444742, 43.904543], [-79.445549, 43.907563], [-79.446548, 43.911482], [-79.447089, 43.913846], [-79.447782, 43.916541], [-79.449992, 43.922505], [-79.455375, 43.921461], [-79.45624, 43.921204], [-79.460666, 43.920277], [-79.466628, 43.918963], [-79.470681, 43.91809], [-79.474282, 43.91729], [-79.472352, 43.91349], [-79.469747, 43.913809], [-79.468202, 43.910365], [-79.467778, 43.906634], [-79.466312, 43.903792], [-79.464415, 43.903747], [-79.460084, 43.90476], [-79.458044, 43.905151], [-79.455247, 43.905749], [-79.452194, 43.907695], [-79.452893, 43.909438], [-79.455718, 43.909866], [-79.459239, 43.911111], [-79.460927, 43.913656], [-79.456688, 43.914955], [-79.451411, 43.914303], [-79.447832, 43.913892], [-79.446945, 43.911874], [-79.446084, 43.908107], [-79.440169, 43.901903], [-79.439356, 43.896475], [-79.439173, 43.895565], [-79.441887, 43.89471]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_0e58e5992e07e08eb5be115d552f40fc.bindTooltip(
                `<div>
                     81 INSPIRATION
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_0e58e5992e07e08eb5be115d552f40fc.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_6737fcc55d728743efae7829a5740832_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#806A50", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_6737fcc55d728743efae7829a5740832_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_6737fcc55d728743efae7829a5740832 = L.geoJson(null, {
                onEachFeature: geo_json_6737fcc55d728743efae7829a5740832_onEachFeature,
            
                style: geo_json_6737fcc55d728743efae7829a5740832_styler,
            ...{
}
        });

        function geo_json_6737fcc55d728743efae7829a5740832_add (data) {
            geo_json_6737fcc55d728743efae7829a5740832
                .addData(data);
        }
            geo_json_6737fcc55d728743efae7829a5740832_add({"features": [{"geometry": {"coordinates": [[-79.441887, 43.89471], [-79.443299, 43.89848], [-79.444081, 43.901573], [-79.444742, 43.904543], [-79.445549, 43.907563], [-79.446548, 43.911482], [-79.448259, 43.913919], [-79.451679, 43.91464], [-79.455704, 43.915314], [-79.459875, 43.914365], [-79.461059, 43.913696], [-79.459624, 43.911194], [-79.45621, 43.909644], [-79.453441, 43.909727], [-79.452108, 43.907121], [-79.454539, 43.906133], [-79.457498, 43.905471], [-79.460531, 43.904807], [-79.465812, 43.903649], [-79.466222, 43.904196], [-79.467586, 43.906514], [-79.468054, 43.909855], [-79.469936, 43.913895], [-79.474154, 43.913424], [-79.475123, 43.916746], [-79.471131, 43.917816], [-79.46717, 43.91865], [-79.461011, 43.920002], [-79.456222, 43.921096], [-79.449648, 43.922405], [-79.448117, 43.916596], [-79.447534, 43.914257], [-79.446945, 43.911874], [-79.446084, 43.908107], [-79.445298, 43.90495], [-79.444488, 43.901299], [-79.443908, 43.898838], [-79.441887, 43.89471]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_6737fcc55d728743efae7829a5740832.bindTooltip(
                `<div>
                     81 INSPIRATION
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_6737fcc55d728743efae7829a5740832.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_d97e17c823160ca29fdb51762318cd12_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#806A50", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_d97e17c823160ca29fdb51762318cd12_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_d97e17c823160ca29fdb51762318cd12 = L.geoJson(null, {
                onEachFeature: geo_json_d97e17c823160ca29fdb51762318cd12_onEachFeature,
            
                style: geo_json_d97e17c823160ca29fdb51762318cd12_styler,
            ...{
}
        });

        function geo_json_d97e17c823160ca29fdb51762318cd12_add (data) {
            geo_json_d97e17c823160ca29fdb51762318cd12
                .addData(data);
        }
            geo_json_d97e17c823160ca29fdb51762318cd12_add({"features": [{"geometry": {"coordinates": [[-79.441887, 43.89471], [-79.439046, 43.895895], [-79.440369, 43.902767], [-79.440836, 43.905496], [-79.445549, 43.907563], [-79.446548, 43.911482], [-79.448259, 43.913919], [-79.451679, 43.91464], [-79.455704, 43.915314], [-79.459875, 43.914365], [-79.461059, 43.913696], [-79.459624, 43.911194], [-79.45621, 43.909644], [-79.453441, 43.909727], [-79.452108, 43.907121], [-79.454539, 43.906133], [-79.457498, 43.905471], [-79.460531, 43.904807], [-79.465812, 43.903649], [-79.466222, 43.904196], [-79.467586, 43.906514], [-79.468054, 43.909855], [-79.469936, 43.913895], [-79.474154, 43.913424], [-79.475123, 43.916746], [-79.471131, 43.917816], [-79.46717, 43.91865], [-79.461011, 43.920002], [-79.456222, 43.921096], [-79.449648, 43.922405], [-79.448117, 43.916596], [-79.447534, 43.914257], [-79.446945, 43.911874], [-79.446084, 43.908107], [-79.445298, 43.90495], [-79.444488, 43.901299], [-79.443908, 43.898838], [-79.441887, 43.89471]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_d97e17c823160ca29fdb51762318cd12.bindTooltip(
                `<div>
                     81 INSPIRATION
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_d97e17c823160ca29fdb51762318cd12.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_4f86a2eb590f85fb39b7ee5a44927fcd_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0095DA", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_4f86a2eb590f85fb39b7ee5a44927fcd_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_4f86a2eb590f85fb39b7ee5a44927fcd = L.geoJson(null, {
                onEachFeature: geo_json_4f86a2eb590f85fb39b7ee5a44927fcd_onEachFeature,
            
                style: geo_json_4f86a2eb590f85fb39b7ee5a44927fcd_styler,
            ...{
}
        });

        function geo_json_4f86a2eb590f85fb39b7ee5a44927fcd_add (data) {
            geo_json_4f86a2eb590f85fb39b7ee5a44927fcd
                .addData(data);
        }
            geo_json_4f86a2eb590f85fb39b7ee5a44927fcd_add({"features": [{"geometry": {"coordinates": [[-79.381612, 43.839414], [-79.384056, 43.840264], [-79.38645, 43.839276], [-79.388521, 43.838226], [-79.390983, 43.838584], [-79.391724, 43.839852], [-79.391539, 43.84196], [-79.392126, 43.843585], [-79.393014, 43.845719], [-79.396029, 43.845538], [-79.398935, 43.845645], [-79.399896, 43.847533], [-79.400872, 43.849594], [-79.401417, 43.852846], [-79.40138, 43.854758], [-79.401257, 43.856093], [-79.39877, 43.857242], [-79.395589, 43.85871], [-79.395887, 43.860189], [-79.398737, 43.863827], [-79.40031, 43.866207], [-79.40094, 43.86966], [-79.401671, 43.871023], [-79.40352, 43.87278], [-79.404466, 43.874286], [-79.40598, 43.87612], [-79.410404, 43.877656], [-79.407608, 43.878537], [-79.408032, 43.881204], [-79.40606, 43.88132], [-79.401875, 43.881625], [-79.402674, 43.883507], [-79.405608, 43.885269], [-79.407597, 43.887483], [-79.408924, 43.889918], [-79.412219, 43.891862], [-79.412762, 43.894178], [-79.409658, 43.895231], [-79.404685, 43.896339], [-79.401084, 43.897093], [-79.400725, 43.896524]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_4f86a2eb590f85fb39b7ee5a44927fcd.bindTooltip(
                `<div>
                     82 VALLEYMEDE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_4f86a2eb590f85fb39b7ee5a44927fcd.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_a498e1705bc624e9747516348aa9506b_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0095DA", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_a498e1705bc624e9747516348aa9506b_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_a498e1705bc624e9747516348aa9506b = L.geoJson(null, {
                onEachFeature: geo_json_a498e1705bc624e9747516348aa9506b_onEachFeature,
            
                style: geo_json_a498e1705bc624e9747516348aa9506b_styler,
            ...{
}
        });

        function geo_json_a498e1705bc624e9747516348aa9506b_add (data) {
            geo_json_a498e1705bc624e9747516348aa9506b
                .addData(data);
        }
            geo_json_a498e1705bc624e9747516348aa9506b_add({"features": [{"geometry": {"coordinates": [[-79.381612, 43.839414], [-79.384056, 43.840264], [-79.38645, 43.839276], [-79.388521, 43.838226], [-79.390983, 43.838584], [-79.391724, 43.839852], [-79.391539, 43.84196], [-79.392126, 43.843585], [-79.393014, 43.845719], [-79.396029, 43.845538], [-79.398935, 43.845645], [-79.399896, 43.847533], [-79.400872, 43.849594], [-79.401417, 43.852846], [-79.40138, 43.854758], [-79.401257, 43.856093], [-79.39877, 43.857242], [-79.395589, 43.85871], [-79.395887, 43.860189], [-79.398737, 43.863827], [-79.40031, 43.866207], [-79.40094, 43.86966], [-79.401671, 43.871023], [-79.40352, 43.87278], [-79.404466, 43.874286], [-79.40598, 43.87612], [-79.410404, 43.877656], [-79.407608, 43.878537], [-79.408032, 43.881204], [-79.40606, 43.88132], [-79.401875, 43.881625], [-79.402674, 43.883507], [-79.405608, 43.885269], [-79.407597, 43.887483], [-79.408924, 43.889918], [-79.412219, 43.891862], [-79.412762, 43.894178], [-79.409658, 43.895231], [-79.404685, 43.896339], [-79.401084, 43.897093], [-79.396114, 43.90054], [-79.398484, 43.902467], [-79.396565, 43.900932], [-79.396041, 43.898855], [-79.39687, 43.898337], [-79.400402, 43.897487], [-79.400725, 43.896524]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_a498e1705bc624e9747516348aa9506b.bindTooltip(
                `<div>
                     82 VALLEYMEDE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_a498e1705bc624e9747516348aa9506b.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_6bc4ab06e852326e2edf711aeaeb0bf0_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0095DA", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_6bc4ab06e852326e2edf711aeaeb0bf0_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_6bc4ab06e852326e2edf711aeaeb0bf0 = L.geoJson(null, {
                onEachFeature: geo_json_6bc4ab06e852326e2edf711aeaeb0bf0_onEachFeature,
            
                style: geo_json_6bc4ab06e852326e2edf711aeaeb0bf0_styler,
            ...{
}
        });

        function geo_json_6bc4ab06e852326e2edf711aeaeb0bf0_add (data) {
            geo_json_6bc4ab06e852326e2edf711aeaeb0bf0
                .addData(data);
        }
            geo_json_6bc4ab06e852326e2edf711aeaeb0bf0_add({"features": [{"geometry": {"coordinates": [[-79.376713, 43.83482], [-79.380956, 43.840048], [-79.381461, 43.841807], [-79.376726, 43.843372], [-79.375301, 43.841872], [-79.376974, 43.840397], [-79.378873, 43.839784], [-79.381612, 43.839414], [-79.384056, 43.840264], [-79.38645, 43.839276], [-79.388521, 43.838226], [-79.390983, 43.838584], [-79.391724, 43.839852], [-79.391539, 43.84196], [-79.392126, 43.843585], [-79.393014, 43.845719], [-79.396029, 43.845538], [-79.398935, 43.845645], [-79.399896, 43.847533], [-79.400872, 43.849594], [-79.401417, 43.852846], [-79.40138, 43.854758], [-79.401257, 43.856093], [-79.39877, 43.857242], [-79.395589, 43.85871], [-79.395887, 43.860189], [-79.398737, 43.863827], [-79.40031, 43.866207], [-79.40094, 43.86966], [-79.401671, 43.871023], [-79.40352, 43.87278], [-79.404466, 43.874286], [-79.40598, 43.87612], [-79.410404, 43.877656], [-79.407608, 43.878537], [-79.408032, 43.881204], [-79.40606, 43.88132], [-79.401875, 43.881625], [-79.402674, 43.883507], [-79.405608, 43.885269], [-79.407597, 43.887483], [-79.408924, 43.889918], [-79.412219, 43.891862], [-79.412762, 43.894178], [-79.409658, 43.895231], [-79.404685, 43.896339], [-79.401084, 43.897093], [-79.400725, 43.896524]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_6bc4ab06e852326e2edf711aeaeb0bf0.bindTooltip(
                `<div>
                     82 VALLEYMEDE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_6bc4ab06e852326e2edf711aeaeb0bf0.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_61df7feb275eef9782ae0e3aae7b9b06_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0095DA", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_61df7feb275eef9782ae0e3aae7b9b06_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_61df7feb275eef9782ae0e3aae7b9b06 = L.geoJson(null, {
                onEachFeature: geo_json_61df7feb275eef9782ae0e3aae7b9b06_onEachFeature,
            
                style: geo_json_61df7feb275eef9782ae0e3aae7b9b06_styler,
            ...{
}
        });

        function geo_json_61df7feb275eef9782ae0e3aae7b9b06_add (data) {
            geo_json_61df7feb275eef9782ae0e3aae7b9b06
                .addData(data);
        }
            geo_json_61df7feb275eef9782ae0e3aae7b9b06_add({"features": [{"geometry": {"coordinates": [[-79.400725, 43.896524], [-79.400286, 43.894752], [-79.40039, 43.89306], [-79.400388, 43.889652], [-79.403824, 43.887843], [-79.407531, 43.887709], [-79.405279, 43.885052], [-79.402931, 43.883652], [-79.402256, 43.881646], [-79.404775, 43.881298], [-79.407927, 43.881372], [-79.407255, 43.87882], [-79.406692, 43.877228], [-79.410471, 43.877827], [-79.407608, 43.878537], [-79.406692, 43.877228], [-79.404697, 43.874521], [-79.402128, 43.871358], [-79.401045, 43.869392], [-79.400527, 43.866438], [-79.399034, 43.863944], [-79.396246, 43.860519], [-79.395704, 43.858952], [-79.398645, 43.857362], [-79.401239, 43.856403], [-79.401484, 43.854963], [-79.401592, 43.853404], [-79.401193, 43.849848], [-79.400187, 43.847745], [-79.399216, 43.8458], [-79.396302, 43.845397], [-79.393373, 43.845747], [-79.392381, 43.844199], [-79.392012, 43.842615], [-79.391904, 43.840135], [-79.388262, 43.838129], [-79.386521, 43.838841], [-79.383881, 43.840137], [-79.381316, 43.83931], [-79.379788, 43.833875]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_61df7feb275eef9782ae0e3aae7b9b06.bindTooltip(
                `<div>
                     82 VALLEYMEDE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_61df7feb275eef9782ae0e3aae7b9b06.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_964b37d2e86e0bc6c8ec2cadbe0d6322_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0095DA", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_964b37d2e86e0bc6c8ec2cadbe0d6322_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_964b37d2e86e0bc6c8ec2cadbe0d6322 = L.geoJson(null, {
                onEachFeature: geo_json_964b37d2e86e0bc6c8ec2cadbe0d6322_onEachFeature,
            
                style: geo_json_964b37d2e86e0bc6c8ec2cadbe0d6322_styler,
            ...{
}
        });

        function geo_json_964b37d2e86e0bc6c8ec2cadbe0d6322_add (data) {
            geo_json_964b37d2e86e0bc6c8ec2cadbe0d6322
                .addData(data);
        }
            geo_json_964b37d2e86e0bc6c8ec2cadbe0d6322_add({"features": [{"geometry": {"coordinates": [[-79.400725, 43.896524], [-79.400286, 43.894752], [-79.40039, 43.89306], [-79.400388, 43.889652], [-79.403824, 43.887843], [-79.407531, 43.887709], [-79.405279, 43.885052], [-79.402931, 43.883652], [-79.402256, 43.881646], [-79.404775, 43.881298], [-79.407927, 43.881372], [-79.407255, 43.87882], [-79.406692, 43.877228], [-79.410471, 43.877827], [-79.407608, 43.878537], [-79.406692, 43.877228], [-79.404697, 43.874521], [-79.402128, 43.871358], [-79.401045, 43.869392], [-79.400527, 43.866438], [-79.399034, 43.863944], [-79.396246, 43.860519], [-79.395704, 43.858952], [-79.398645, 43.857362], [-79.401239, 43.856403], [-79.401484, 43.854963], [-79.401592, 43.853404], [-79.401193, 43.849848], [-79.400187, 43.847745], [-79.399216, 43.8458], [-79.396302, 43.845397], [-79.393373, 43.845747], [-79.392381, 43.844199], [-79.392012, 43.842615], [-79.391904, 43.840135], [-79.388262, 43.838129], [-79.386521, 43.838841], [-79.383881, 43.840137], [-79.381461, 43.841807], [-79.376726, 43.843372], [-79.375301, 43.841872], [-79.376974, 43.840397], [-79.378873, 43.839784], [-79.381612, 43.839414]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_964b37d2e86e0bc6c8ec2cadbe0d6322.bindTooltip(
                `<div>
                     82 VALLEYMEDE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_964b37d2e86e0bc6c8ec2cadbe0d6322.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_5214acd4bd9c8e536d2db994efdc3fcd_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#72BF44", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_5214acd4bd9c8e536d2db994efdc3fcd_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_5214acd4bd9c8e536d2db994efdc3fcd = L.geoJson(null, {
                onEachFeature: geo_json_5214acd4bd9c8e536d2db994efdc3fcd_onEachFeature,
            
                style: geo_json_5214acd4bd9c8e536d2db994efdc3fcd_styler,
            ...{
}
        });

        function geo_json_5214acd4bd9c8e536d2db994efdc3fcd_add (data) {
            geo_json_5214acd4bd9c8e536d2db994efdc3fcd
                .addData(data);
        }
            geo_json_5214acd4bd9c8e536d2db994efdc3fcd_add({"features": [{"geometry": {"coordinates": [[-79.42546, 43.839813], [-79.430269, 43.839232], [-79.436214, 43.837963], [-79.43694, 43.83945], [-79.436835, 43.840946], [-79.437352, 43.842926], [-79.438092, 43.844814], [-79.438091, 43.84692], [-79.440083, 43.84663], [-79.443551, 43.845938], [-79.444146, 43.847395], [-79.445317, 43.850283], [-79.445604, 43.852316], [-79.440679, 43.852971], [-79.438975, 43.854824], [-79.439376, 43.857064], [-79.440563, 43.858848], [-79.444738, 43.858199], [-79.445533, 43.860459], [-79.446245, 43.86243], [-79.446993, 43.864496], [-79.445548, 43.86715], [-79.448628, 43.868421], [-79.449247, 43.869988], [-79.45066, 43.873738], [-79.45123, 43.875799], [-79.454363, 43.875387], [-79.456274, 43.874972], [-79.460058, 43.874171], [-79.460349, 43.875901], [-79.461911, 43.877568], [-79.462097, 43.878953], [-79.459067, 43.880494], [-79.456888, 43.880906], [-79.453652, 43.880399], [-79.450985, 43.881129], [-79.451475, 43.88466], [-79.452059, 43.886842], [-79.457556, 43.886255], [-79.460382, 43.885606], [-79.463536, 43.884979], [-79.466976, 43.884296], [-79.468179, 43.888451], [-79.469466, 43.893874], [-79.466186, 43.895251], [-79.462229, 43.896075], [-79.457803, 43.895321], [-79.455697, 43.893368], [-79.454339, 43.891684], [-79.448027, 43.892868], [-79.445538, 43.893705], [-79.443054, 43.894677], [-79.441694, 43.894956]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_5214acd4bd9c8e536d2db994efdc3fcd.bindTooltip(
                `<div>
                     83 TRENCH
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_5214acd4bd9c8e536d2db994efdc3fcd.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_a9e591d0e2528526696c70d243ce9a20_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#72BF44", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_a9e591d0e2528526696c70d243ce9a20_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_a9e591d0e2528526696c70d243ce9a20 = L.geoJson(null, {
                onEachFeature: geo_json_a9e591d0e2528526696c70d243ce9a20_onEachFeature,
            
                style: geo_json_a9e591d0e2528526696c70d243ce9a20_styler,
            ...{
}
        });

        function geo_json_a9e591d0e2528526696c70d243ce9a20_add (data) {
            geo_json_a9e591d0e2528526696c70d243ce9a20
                .addData(data);
        }
            geo_json_a9e591d0e2528526696c70d243ce9a20_add({"features": [{"geometry": {"coordinates": [[-79.42546, 43.839813], [-79.430269, 43.839232], [-79.436214, 43.837963], [-79.43694, 43.83945], [-79.436835, 43.840946], [-79.437352, 43.842926], [-79.438092, 43.844814], [-79.438091, 43.84692], [-79.440083, 43.84663], [-79.443551, 43.845938], [-79.444146, 43.847395], [-79.445317, 43.850283], [-79.445604, 43.852316], [-79.440679, 43.852971], [-79.438975, 43.854824], [-79.439376, 43.857064], [-79.440563, 43.858848], [-79.444738, 43.858199], [-79.445533, 43.860459], [-79.446245, 43.86243], [-79.446993, 43.864496], [-79.445548, 43.86715], [-79.448628, 43.868421], [-79.449247, 43.869988], [-79.45066, 43.873738], [-79.45123, 43.875799], [-79.454363, 43.875387], [-79.456274, 43.874972], [-79.460058, 43.874171], [-79.460349, 43.875901], [-79.461911, 43.877568], [-79.462097, 43.878953], [-79.459067, 43.880494], [-79.456888, 43.880906], [-79.453652, 43.880399], [-79.450985, 43.881129], [-79.451475, 43.88466], [-79.452059, 43.886842], [-79.457556, 43.886255], [-79.460382, 43.885606], [-79.463536, 43.884979], [-79.466976, 43.884296], [-79.468179, 43.888451], [-79.469466, 43.893874], [-79.466186, 43.895251], [-79.462229, 43.896075], [-79.457803, 43.895321], [-79.455697, 43.893368], [-79.454339, 43.891684], [-79.448027, 43.892868], [-79.445538, 43.893705], [-79.443054, 43.894677], [-79.441694, 43.894956], [-79.439046, 43.895895], [-79.4393, 43.899319], [-79.440369, 43.902767], [-79.440836, 43.905496]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_a9e591d0e2528526696c70d243ce9a20.bindTooltip(
                `<div>
                     83 TRENCH
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_a9e591d0e2528526696c70d243ce9a20.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_55ed43e6a3593454080a1149359c2ecc_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#72BF44", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_55ed43e6a3593454080a1149359c2ecc_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_55ed43e6a3593454080a1149359c2ecc = L.geoJson(null, {
                onEachFeature: geo_json_55ed43e6a3593454080a1149359c2ecc_onEachFeature,
            
                style: geo_json_55ed43e6a3593454080a1149359c2ecc_styler,
            ...{
}
        });

        function geo_json_55ed43e6a3593454080a1149359c2ecc_add (data) {
            geo_json_55ed43e6a3593454080a1149359c2ecc
                .addData(data);
        }
            geo_json_55ed43e6a3593454080a1149359c2ecc_add({"features": [{"geometry": {"coordinates": [[-79.42546, 43.839813], [-79.430269, 43.839232], [-79.436214, 43.837963], [-79.43694, 43.83945], [-79.436835, 43.840946], [-79.437352, 43.842926], [-79.438092, 43.844814], [-79.438091, 43.84692], [-79.440083, 43.84663], [-79.443551, 43.845938], [-79.444146, 43.847395], [-79.445317, 43.850283], [-79.445604, 43.852316], [-79.440679, 43.852971], [-79.438975, 43.854824], [-79.439376, 43.857064], [-79.440563, 43.858848], [-79.444738, 43.858199], [-79.445533, 43.860459], [-79.446245, 43.86243], [-79.446993, 43.864496], [-79.445548, 43.86715], [-79.448628, 43.868421], [-79.449247, 43.869988], [-79.45066, 43.873738], [-79.45123, 43.875799], [-79.454363, 43.875387], [-79.456274, 43.874972], [-79.460058, 43.874171], [-79.460349, 43.875901], [-79.461911, 43.877568], [-79.462097, 43.878953], [-79.459067, 43.880494], [-79.456888, 43.880906], [-79.453652, 43.880399], [-79.450985, 43.881129], [-79.451475, 43.88466], [-79.452059, 43.886842], [-79.454094, 43.89149], [-79.448027, 43.892868], [-79.445538, 43.893705], [-79.443054, 43.894677], [-79.441694, 43.894956]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_55ed43e6a3593454080a1149359c2ecc.bindTooltip(
                `<div>
                     83 TRENCH
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_55ed43e6a3593454080a1149359c2ecc.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_aa978d623dacfeef26654fc53560dcc8_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#72BF44", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_aa978d623dacfeef26654fc53560dcc8_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_aa978d623dacfeef26654fc53560dcc8 = L.geoJson(null, {
                onEachFeature: geo_json_aa978d623dacfeef26654fc53560dcc8_onEachFeature,
            
                style: geo_json_aa978d623dacfeef26654fc53560dcc8_styler,
            ...{
}
        });

        function geo_json_aa978d623dacfeef26654fc53560dcc8_add (data) {
            geo_json_aa978d623dacfeef26654fc53560dcc8
                .addData(data);
        }
            geo_json_aa978d623dacfeef26654fc53560dcc8_add({"features": [{"geometry": {"coordinates": [[-79.42546, 43.839813], [-79.430269, 43.839232], [-79.436214, 43.837963], [-79.43694, 43.83945], [-79.436835, 43.840946], [-79.437352, 43.842926], [-79.438092, 43.844814], [-79.438091, 43.84692], [-79.440083, 43.84663], [-79.443551, 43.845938], [-79.444146, 43.847395], [-79.445317, 43.850283], [-79.445604, 43.852316], [-79.440679, 43.852971], [-79.438975, 43.854824], [-79.439376, 43.857064], [-79.440563, 43.858848], [-79.444738, 43.858199], [-79.445533, 43.860459], [-79.446245, 43.86243], [-79.446993, 43.864496], [-79.445548, 43.86715], [-79.448628, 43.868421], [-79.449247, 43.869988], [-79.45066, 43.873738], [-79.45123, 43.875799], [-79.454363, 43.875387], [-79.456274, 43.874972], [-79.460058, 43.874171], [-79.460349, 43.875901], [-79.461911, 43.877568], [-79.462097, 43.878953], [-79.459067, 43.880494], [-79.456888, 43.880906], [-79.453652, 43.880399], [-79.450985, 43.881129], [-79.451475, 43.88466], [-79.452059, 43.886842], [-79.454094, 43.89149], [-79.448027, 43.892868], [-79.445538, 43.893705], [-79.443054, 43.894677], [-79.441694, 43.894956], [-79.439046, 43.895895], [-79.4393, 43.899319], [-79.440369, 43.902767], [-79.440836, 43.905496]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_aa978d623dacfeef26654fc53560dcc8.bindTooltip(
                `<div>
                     83 TRENCH
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_aa978d623dacfeef26654fc53560dcc8.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_ab58b6de178a4536a5f8a59df452c3d6_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#72BF44", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_ab58b6de178a4536a5f8a59df452c3d6_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_ab58b6de178a4536a5f8a59df452c3d6 = L.geoJson(null, {
                onEachFeature: geo_json_ab58b6de178a4536a5f8a59df452c3d6_onEachFeature,
            
                style: geo_json_ab58b6de178a4536a5f8a59df452c3d6_styler,
            ...{
}
        });

        function geo_json_ab58b6de178a4536a5f8a59df452c3d6_add (data) {
            geo_json_ab58b6de178a4536a5f8a59df452c3d6
                .addData(data);
        }
            geo_json_ab58b6de178a4536a5f8a59df452c3d6_add({"features": [{"geometry": {"coordinates": [[-79.441694, 43.894956], [-79.439046, 43.895895], [-79.440335, 43.899402], [-79.441911, 43.899041], [-79.44295, 43.895054], [-79.445329, 43.893989], [-79.448492, 43.892878], [-79.45406, 43.891661], [-79.452415, 43.887493], [-79.451736, 43.88496], [-79.450972, 43.881431], [-79.45457, 43.880639], [-79.456523, 43.88098], [-79.458798, 43.880694], [-79.462375, 43.879029], [-79.462131, 43.877554], [-79.460569, 43.876119], [-79.459573, 43.874179], [-79.456629, 43.874836], [-79.454703, 43.875247], [-79.451593, 43.875865], [-79.450897, 43.874279], [-79.449496, 43.869987], [-79.44905, 43.86894], [-79.448577, 43.867894], [-79.445925, 43.867271], [-79.447055, 43.86483], [-79.446477, 43.862705], [-79.445821, 43.860887], [-79.445164, 43.858318], [-79.440848, 43.858897], [-79.439657, 43.857251], [-79.438977, 43.855631], [-79.440445, 43.853094], [-79.44583, 43.852181], [-79.445608, 43.85071], [-79.44454, 43.848033], [-79.443838, 43.845944], [-79.440723, 43.846405], [-79.438173, 43.846739], [-79.438166, 43.845127], [-79.43757, 43.84312], [-79.437037, 43.841202], [-79.437065, 43.839268], [-79.436466, 43.838049], [-79.430101, 43.8391], [-79.42546, 43.839813]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_ab58b6de178a4536a5f8a59df452c3d6.bindTooltip(
                `<div>
                     83 TRENCH
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_ab58b6de178a4536a5f8a59df452c3d6.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_b244743f51187e2f34f1240375ae2c75_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#72BF44", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_b244743f51187e2f34f1240375ae2c75_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_b244743f51187e2f34f1240375ae2c75 = L.geoJson(null, {
                onEachFeature: geo_json_b244743f51187e2f34f1240375ae2c75_onEachFeature,
            
                style: geo_json_b244743f51187e2f34f1240375ae2c75_styler,
            ...{
}
        });

        function geo_json_b244743f51187e2f34f1240375ae2c75_add (data) {
            geo_json_b244743f51187e2f34f1240375ae2c75
                .addData(data);
        }
            geo_json_b244743f51187e2f34f1240375ae2c75_add({"features": [{"geometry": {"coordinates": [[-79.440836, 43.905496], [-79.444488, 43.901299], [-79.443908, 43.898838], [-79.44295, 43.895054], [-79.445329, 43.893989], [-79.448492, 43.892878], [-79.45406, 43.891661], [-79.455428, 43.89333], [-79.457429, 43.895149], [-79.461778, 43.896238], [-79.466174, 43.895388], [-79.468936, 43.894405], [-79.466513, 43.884222], [-79.462686, 43.884967], [-79.460766, 43.885405], [-79.457958, 43.886002], [-79.45251, 43.887152], [-79.451736, 43.88496], [-79.450972, 43.881431], [-79.45457, 43.880639], [-79.456523, 43.88098], [-79.458798, 43.880694], [-79.462375, 43.879029], [-79.462131, 43.877554], [-79.460569, 43.876119], [-79.459573, 43.874179], [-79.456629, 43.874836], [-79.454703, 43.875247], [-79.451593, 43.875865], [-79.450897, 43.874279], [-79.449496, 43.869987], [-79.44905, 43.86894], [-79.448577, 43.867894], [-79.445925, 43.867271], [-79.447055, 43.86483], [-79.446477, 43.862705], [-79.445821, 43.860887], [-79.445164, 43.858318], [-79.440848, 43.858897], [-79.439657, 43.857251], [-79.438977, 43.855631], [-79.440445, 43.853094], [-79.44583, 43.852181], [-79.445608, 43.85071], [-79.44454, 43.848033], [-79.443838, 43.845944], [-79.440723, 43.846405], [-79.438173, 43.846739], [-79.438166, 43.845127], [-79.43757, 43.84312], [-79.437037, 43.841202], [-79.437065, 43.839268], [-79.436466, 43.838049], [-79.430101, 43.8391], [-79.42546, 43.839813]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_b244743f51187e2f34f1240375ae2c75.bindTooltip(
                `<div>
                     83 TRENCH
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_b244743f51187e2f34f1240375ae2c75.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_ae80a4270d6d1c20ccb500db452ff52b_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#72BF44", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_ae80a4270d6d1c20ccb500db452ff52b_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_ae80a4270d6d1c20ccb500db452ff52b = L.geoJson(null, {
                onEachFeature: geo_json_ae80a4270d6d1c20ccb500db452ff52b_onEachFeature,
            
                style: geo_json_ae80a4270d6d1c20ccb500db452ff52b_styler,
            ...{
}
        });

        function geo_json_ae80a4270d6d1c20ccb500db452ff52b_add (data) {
            geo_json_ae80a4270d6d1c20ccb500db452ff52b
                .addData(data);
        }
            geo_json_ae80a4270d6d1c20ccb500db452ff52b_add({"features": [{"geometry": {"coordinates": [[-79.440836, 43.905496], [-79.444488, 43.901299], [-79.443908, 43.898838], [-79.44295, 43.895054], [-79.445329, 43.893989], [-79.448492, 43.892878], [-79.45406, 43.891661], [-79.452415, 43.887493], [-79.451736, 43.88496], [-79.450972, 43.881431], [-79.45457, 43.880639], [-79.456523, 43.88098], [-79.458798, 43.880694], [-79.462375, 43.879029], [-79.462131, 43.877554], [-79.460569, 43.876119], [-79.459573, 43.874179], [-79.456629, 43.874836], [-79.454703, 43.875247], [-79.451593, 43.875865], [-79.450897, 43.874279], [-79.449496, 43.869987], [-79.44905, 43.86894], [-79.448577, 43.867894], [-79.445925, 43.867271], [-79.447055, 43.86483], [-79.446477, 43.862705], [-79.445821, 43.860887], [-79.445164, 43.858318], [-79.440848, 43.858897], [-79.439657, 43.857251], [-79.438977, 43.855631], [-79.440445, 43.853094], [-79.44583, 43.852181], [-79.445608, 43.85071], [-79.44454, 43.848033], [-79.443838, 43.845944], [-79.440723, 43.846405], [-79.438173, 43.846739], [-79.438166, 43.845127], [-79.43757, 43.84312], [-79.437037, 43.841202], [-79.437065, 43.839268], [-79.436466, 43.838049], [-79.430101, 43.8391], [-79.42546, 43.839813]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_ae80a4270d6d1c20ccb500db452ff52b.bindTooltip(
                `<div>
                     83 TRENCH
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_ae80a4270d6d1c20ccb500db452ff52b.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_b064b29218e34642d394c1fc413e14b2_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#72BF44", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_b064b29218e34642d394c1fc413e14b2_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_b064b29218e34642d394c1fc413e14b2 = L.geoJson(null, {
                onEachFeature: geo_json_b064b29218e34642d394c1fc413e14b2_onEachFeature,
            
                style: geo_json_b064b29218e34642d394c1fc413e14b2_styler,
            ...{
}
        });

        function geo_json_b064b29218e34642d394c1fc413e14b2_add (data) {
            geo_json_b064b29218e34642d394c1fc413e14b2
                .addData(data);
        }
            geo_json_b064b29218e34642d394c1fc413e14b2_add({"features": [{"geometry": {"coordinates": [[-79.441694, 43.894956], [-79.439046, 43.895895], [-79.440335, 43.899402], [-79.441911, 43.899041], [-79.44295, 43.895054], [-79.445329, 43.893989], [-79.448492, 43.892878], [-79.45406, 43.891661], [-79.455428, 43.89333], [-79.457429, 43.895149], [-79.461778, 43.896238], [-79.466174, 43.895388], [-79.468936, 43.894405], [-79.466513, 43.884222], [-79.462686, 43.884967], [-79.460766, 43.885405], [-79.457958, 43.886002], [-79.45251, 43.887152], [-79.451736, 43.88496], [-79.450972, 43.881431], [-79.45457, 43.880639], [-79.456523, 43.88098], [-79.458798, 43.880694], [-79.462375, 43.879029], [-79.462131, 43.877554], [-79.460569, 43.876119], [-79.459573, 43.874179], [-79.456629, 43.874836], [-79.454703, 43.875247], [-79.451593, 43.875865], [-79.450897, 43.874279], [-79.449496, 43.869987], [-79.44905, 43.86894], [-79.448577, 43.867894], [-79.445925, 43.867271], [-79.447055, 43.86483], [-79.446477, 43.862705], [-79.445821, 43.860887], [-79.445164, 43.858318], [-79.440848, 43.858897], [-79.439657, 43.857251], [-79.438977, 43.855631], [-79.440445, 43.853094], [-79.44583, 43.852181], [-79.445608, 43.85071], [-79.44454, 43.848033], [-79.443838, 43.845944], [-79.440723, 43.846405], [-79.438173, 43.846739], [-79.438166, 43.845127], [-79.43757, 43.84312], [-79.437037, 43.841202], [-79.437065, 43.839268], [-79.436466, 43.838049], [-79.430101, 43.8391], [-79.42546, 43.839813]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_b064b29218e34642d394c1fc413e14b2.bindTooltip(
                `<div>
                     83 TRENCH
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_b064b29218e34642d394c1fc413e14b2.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_6be6c4f8cafee0809583bc08e0214601_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3238E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_6be6c4f8cafee0809583bc08e0214601_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_6be6c4f8cafee0809583bc08e0214601 = L.geoJson(null, {
                onEachFeature: geo_json_6be6c4f8cafee0809583bc08e0214601_onEachFeature,
            
                style: geo_json_6be6c4f8cafee0809583bc08e0214601_styler,
            ...{
}
        });

        function geo_json_6be6c4f8cafee0809583bc08e0214601_add (data) {
            geo_json_6be6c4f8cafee0809583bc08e0214601
                .addData(data);
        }
            geo_json_6be6c4f8cafee0809583bc08e0214601_add({"features": [{"geometry": {"coordinates": [[-79.616569, 43.813884], [-79.618076, 43.814864], [-79.620676, 43.814527], [-79.623266, 43.815483], [-79.62513, 43.81722], [-79.625605, 43.819785], [-79.624827, 43.821181], [-79.622131, 43.822577], [-79.620199, 43.822973], [-79.617296, 43.823517], [-79.614259, 43.824148], [-79.611034, 43.825414], [-79.609719, 43.825861], [-79.608323, 43.824053], [-79.607108, 43.821969], [-79.603197, 43.818772], [-79.598943, 43.817264], [-79.595808, 43.817917], [-79.581353, 43.821221], [-79.576334, 43.822241], [-79.568376, 43.823841], [-79.563054, 43.824944], [-79.5554, 43.826123], [-79.551817, 43.826688], [-79.539777, 43.829052], [-79.536258, 43.829826], [-79.533053, 43.830632], [-79.53213, 43.827908], [-79.533949, 43.827009], [-79.532409, 43.830627], [-79.52681, 43.832303], [-79.522334, 43.833247], [-79.517633, 43.834339], [-79.51401, 43.83509], [-79.50858, 43.836217], [-79.506422, 43.836717], [-79.502653, 43.838176], [-79.499936, 43.838986], [-79.492587, 43.840558], [-79.487236, 43.841654], [-79.483409, 43.842449], [-79.47708, 43.843803], [-79.470598, 43.845105], [-79.462243, 43.846805], [-79.459176, 43.847478], [-79.453336, 43.848699], [-79.448581, 43.849655], [-79.445704, 43.850264], [-79.440159, 43.851441], [-79.435673, 43.852371], [-79.433448, 43.852814], [-79.431741, 43.853213], [-79.425889, 43.85461], [-79.423976, 43.854918], [-79.421689, 43.855354], [-79.416426, 43.856521], [-79.411293, 43.857634], [-79.403154, 43.858649], [-79.396414, 43.860144], [-79.389549, 43.861649], [-79.387236, 43.862243], [-79.384401, 43.862976], [-79.382504, 43.865499], [-79.385611, 43.867234]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_6be6c4f8cafee0809583bc08e0214601.bindTooltip(
                `<div>
                     85 RUTHERFORD
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_6be6c4f8cafee0809583bc08e0214601.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_a61c811203c0e3a8042dda071584fb2a_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3238E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_a61c811203c0e3a8042dda071584fb2a_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_a61c811203c0e3a8042dda071584fb2a = L.geoJson(null, {
                onEachFeature: geo_json_a61c811203c0e3a8042dda071584fb2a_onEachFeature,
            
                style: geo_json_a61c811203c0e3a8042dda071584fb2a_styler,
            ...{
}
        });

        function geo_json_a61c811203c0e3a8042dda071584fb2a_add (data) {
            geo_json_a61c811203c0e3a8042dda071584fb2a
                .addData(data);
        }
            geo_json_a61c811203c0e3a8042dda071584fb2a_add({"features": [{"geometry": {"coordinates": [[-79.533949, 43.827009], [-79.532409, 43.830627], [-79.52681, 43.832303], [-79.522334, 43.833247], [-79.517633, 43.834339], [-79.51401, 43.83509], [-79.50858, 43.836217], [-79.506422, 43.836717], [-79.502653, 43.838176], [-79.499936, 43.838986], [-79.492587, 43.840558], [-79.487236, 43.841654], [-79.483409, 43.842449], [-79.47708, 43.843803], [-79.470598, 43.845105], [-79.462243, 43.846805], [-79.459176, 43.847478], [-79.453336, 43.848699], [-79.448581, 43.849655], [-79.445704, 43.850264], [-79.440159, 43.851441], [-79.435673, 43.852371], [-79.433448, 43.852814], [-79.431741, 43.853213], [-79.425889, 43.85461], [-79.423976, 43.854918], [-79.421689, 43.855354], [-79.416426, 43.856521], [-79.411293, 43.857634], [-79.403154, 43.858649], [-79.396414, 43.860144], [-79.389549, 43.861649], [-79.387236, 43.862243], [-79.384401, 43.862976], [-79.382504, 43.865499], [-79.385611, 43.867234]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_a61c811203c0e3a8042dda071584fb2a.bindTooltip(
                `<div>
                     85 RUTHERFORD
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_a61c811203c0e3a8042dda071584fb2a.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_26f56e981a6db19c75d581403092b8b0_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3238E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_26f56e981a6db19c75d581403092b8b0_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_26f56e981a6db19c75d581403092b8b0 = L.geoJson(null, {
                onEachFeature: geo_json_26f56e981a6db19c75d581403092b8b0_onEachFeature,
            
                style: geo_json_26f56e981a6db19c75d581403092b8b0_styler,
            ...{
}
        });

        function geo_json_26f56e981a6db19c75d581403092b8b0_add (data) {
            geo_json_26f56e981a6db19c75d581403092b8b0
                .addData(data);
        }
            geo_json_26f56e981a6db19c75d581403092b8b0_add({"features": [{"geometry": {"coordinates": [[-79.385611, 43.867234], [-79.386453, 43.869696], [-79.387789, 43.865758], [-79.387151, 43.862688], [-79.390447, 43.86172], [-79.395588, 43.860576], [-79.40249, 43.859024], [-79.410677, 43.858001], [-79.416038, 43.856802], [-79.421105, 43.855699], [-79.423587, 43.855157], [-79.425478, 43.854879], [-79.43261, 43.85327], [-79.43634, 43.852438], [-79.439784, 43.851728], [-79.445248, 43.850635], [-79.448837, 43.849832], [-79.453123, 43.848964], [-79.455343, 43.8485], [-79.458275, 43.84789], [-79.46167, 43.847164], [-79.469857, 43.84546], [-79.47304, 43.844851], [-79.476325, 43.844183], [-79.482569, 43.84286], [-79.486606, 43.842052], [-79.491921, 43.840926], [-79.500233, 43.839244], [-79.502092, 43.838655], [-79.507436, 43.836714], [-79.513541, 43.835411], [-79.517067, 43.834686], [-79.521677, 43.833661], [-79.526454, 43.832629], [-79.53213, 43.827908], [-79.534178, 43.827276], [-79.538856, 43.829518], [-79.542212, 43.828887], [-79.55202, 43.826906], [-79.555823, 43.826346], [-79.562378, 43.825296], [-79.567447, 43.824281], [-79.575635, 43.82264], [-79.58189, 43.821335], [-79.595246, 43.818276], [-79.600164, 43.817235], [-79.601983, 43.816775], [-79.605667, 43.81591], [-79.610958, 43.814749], [-79.616104, 43.81353], [-79.616569, 43.813884], [-79.618076, 43.814864], [-79.620676, 43.814527], [-79.623266, 43.815483], [-79.62513, 43.81722], [-79.625605, 43.819785], [-79.624827, 43.821181], [-79.622131, 43.822577], [-79.620199, 43.822973], [-79.617296, 43.823517], [-79.614259, 43.824148], [-79.611034, 43.825414], [-79.609719, 43.825861], [-79.608323, 43.824053], [-79.607108, 43.821969]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_26f56e981a6db19c75d581403092b8b0.bindTooltip(
                `<div>
                     85 RUTHERFORD
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_26f56e981a6db19c75d581403092b8b0.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_7ff5b8df7f1c405989674e7512033067_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3238E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_7ff5b8df7f1c405989674e7512033067_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_7ff5b8df7f1c405989674e7512033067 = L.geoJson(null, {
                onEachFeature: geo_json_7ff5b8df7f1c405989674e7512033067_onEachFeature,
            
                style: geo_json_7ff5b8df7f1c405989674e7512033067_styler,
            ...{
}
        });

        function geo_json_7ff5b8df7f1c405989674e7512033067_add (data) {
            geo_json_7ff5b8df7f1c405989674e7512033067
                .addData(data);
        }
            geo_json_7ff5b8df7f1c405989674e7512033067_add({"features": [{"geometry": {"coordinates": [[-79.385611, 43.867234], [-79.386453, 43.869696], [-79.387789, 43.865758], [-79.387151, 43.862688], [-79.390447, 43.86172], [-79.395588, 43.860576], [-79.40249, 43.859024], [-79.410677, 43.858001], [-79.416038, 43.856802], [-79.421105, 43.855699], [-79.423587, 43.855157], [-79.425478, 43.854879], [-79.43261, 43.85327], [-79.43634, 43.852438], [-79.439784, 43.851728], [-79.445248, 43.850635], [-79.448837, 43.849832], [-79.453123, 43.848964], [-79.455343, 43.8485], [-79.458275, 43.84789], [-79.46167, 43.847164], [-79.469857, 43.84546], [-79.47304, 43.844851], [-79.476325, 43.844183], [-79.482569, 43.84286], [-79.486606, 43.842052], [-79.491921, 43.840926], [-79.500233, 43.839244], [-79.502092, 43.838655], [-79.507436, 43.836714], [-79.513541, 43.835411], [-79.517067, 43.834686], [-79.521677, 43.833661], [-79.526454, 43.832629], [-79.53213, 43.827908], [-79.534178, 43.827276], [-79.538856, 43.829518], [-79.542212, 43.828887], [-79.55202, 43.826906], [-79.555823, 43.826346], [-79.562378, 43.825296], [-79.567447, 43.824281], [-79.575635, 43.82264], [-79.58189, 43.821335], [-79.595246, 43.818276], [-79.600164, 43.817235], [-79.601983, 43.816775], [-79.605667, 43.81591], [-79.610958, 43.814749], [-79.616104, 43.81353], [-79.616569, 43.813884]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_7ff5b8df7f1c405989674e7512033067.bindTooltip(
                `<div>
                     85 RUTHERFORD
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_7ff5b8df7f1c405989674e7512033067.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_62d0b0fcb0ca38189d49e4264659f8f6_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3238E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_62d0b0fcb0ca38189d49e4264659f8f6_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_62d0b0fcb0ca38189d49e4264659f8f6 = L.geoJson(null, {
                onEachFeature: geo_json_62d0b0fcb0ca38189d49e4264659f8f6_onEachFeature,
            
                style: geo_json_62d0b0fcb0ca38189d49e4264659f8f6_styler,
            ...{
}
        });

        function geo_json_62d0b0fcb0ca38189d49e4264659f8f6_add (data) {
            geo_json_62d0b0fcb0ca38189d49e4264659f8f6
                .addData(data);
        }
            geo_json_62d0b0fcb0ca38189d49e4264659f8f6_add({"features": [{"geometry": {"coordinates": [[-79.616569, 43.813884], [-79.618076, 43.814864], [-79.620676, 43.814527], [-79.623266, 43.815483], [-79.62513, 43.81722], [-79.625605, 43.819785], [-79.624827, 43.821181], [-79.622131, 43.822577], [-79.620199, 43.822973], [-79.617296, 43.823517], [-79.614259, 43.824148], [-79.611034, 43.825414], [-79.609719, 43.825861], [-79.608323, 43.824053], [-79.607108, 43.821969], [-79.603197, 43.818772], [-79.598943, 43.817264], [-79.595808, 43.817917], [-79.581353, 43.821221], [-79.576334, 43.822241], [-79.568376, 43.823841], [-79.563054, 43.824944], [-79.5554, 43.826123], [-79.551817, 43.826688], [-79.539777, 43.829052], [-79.536258, 43.829826], [-79.533053, 43.830632], [-79.53213, 43.827908], [-79.533949, 43.827009], [-79.532409, 43.830627], [-79.52681, 43.832303], [-79.522334, 43.833247], [-79.517633, 43.834339], [-79.51401, 43.83509], [-79.50858, 43.836217], [-79.506422, 43.836717], [-79.502653, 43.838176], [-79.49967, 43.838683], [-79.499936, 43.838986], [-79.492587, 43.840558], [-79.487236, 43.841654], [-79.483409, 43.842449], [-79.47708, 43.843803], [-79.470598, 43.845105], [-79.462243, 43.846805], [-79.459176, 43.847478], [-79.453336, 43.848699], [-79.448581, 43.849655], [-79.445704, 43.850264], [-79.440159, 43.851441], [-79.435673, 43.852371], [-79.433448, 43.852814], [-79.431741, 43.853213], [-79.425889, 43.85461], [-79.423976, 43.854918], [-79.421689, 43.855354], [-79.416426, 43.856521], [-79.411293, 43.857634], [-79.403154, 43.858649], [-79.396414, 43.860144], [-79.389549, 43.861649], [-79.387236, 43.862243], [-79.384401, 43.862976], [-79.382504, 43.865499], [-79.385611, 43.867234]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_62d0b0fcb0ca38189d49e4264659f8f6.bindTooltip(
                `<div>
                     85 RUTHERFORD
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_62d0b0fcb0ca38189d49e4264659f8f6.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_9dc4e435569e56d192f1053efa5bc6d9_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3238E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_9dc4e435569e56d192f1053efa5bc6d9_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_9dc4e435569e56d192f1053efa5bc6d9 = L.geoJson(null, {
                onEachFeature: geo_json_9dc4e435569e56d192f1053efa5bc6d9_onEachFeature,
            
                style: geo_json_9dc4e435569e56d192f1053efa5bc6d9_styler,
            ...{
}
        });

        function geo_json_9dc4e435569e56d192f1053efa5bc6d9_add (data) {
            geo_json_9dc4e435569e56d192f1053efa5bc6d9
                .addData(data);
        }
            geo_json_9dc4e435569e56d192f1053efa5bc6d9_add({"features": [{"geometry": {"coordinates": [[-79.607108, 43.821969], [-79.603197, 43.818772], [-79.598943, 43.817264], [-79.595808, 43.817917], [-79.581353, 43.821221], [-79.576334, 43.822241], [-79.568376, 43.823841], [-79.563054, 43.824944], [-79.5554, 43.826123], [-79.551817, 43.826688], [-79.539777, 43.829052], [-79.536258, 43.829826], [-79.533053, 43.830632], [-79.53213, 43.827908], [-79.533949, 43.827009], [-79.532409, 43.830627], [-79.52681, 43.832303], [-79.522334, 43.833247], [-79.517633, 43.834339], [-79.51401, 43.83509], [-79.50858, 43.836217], [-79.506422, 43.836717], [-79.502653, 43.838176], [-79.499936, 43.838986], [-79.492587, 43.840558], [-79.487236, 43.841654], [-79.483409, 43.842449], [-79.47708, 43.843803], [-79.470598, 43.845105], [-79.462243, 43.846805], [-79.459176, 43.847478], [-79.453336, 43.848699], [-79.448581, 43.849655], [-79.445704, 43.850264], [-79.440159, 43.851441], [-79.435673, 43.852371], [-79.433448, 43.852814], [-79.431741, 43.853213], [-79.425889, 43.85461], [-79.423976, 43.854918], [-79.421689, 43.855354], [-79.416426, 43.856521], [-79.411293, 43.857634], [-79.403154, 43.858649], [-79.396414, 43.860144], [-79.389549, 43.861649], [-79.387236, 43.862243], [-79.384401, 43.862976], [-79.382504, 43.865499], [-79.385611, 43.867234]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_9dc4e435569e56d192f1053efa5bc6d9.bindTooltip(
                `<div>
                     85 RUTHERFORD
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_9dc4e435569e56d192f1053efa5bc6d9.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_968e15be879e03eff96cf0e0a0bb4727_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3238E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_968e15be879e03eff96cf0e0a0bb4727_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_968e15be879e03eff96cf0e0a0bb4727 = L.geoJson(null, {
                onEachFeature: geo_json_968e15be879e03eff96cf0e0a0bb4727_onEachFeature,
            
                style: geo_json_968e15be879e03eff96cf0e0a0bb4727_styler,
            ...{
}
        });

        function geo_json_968e15be879e03eff96cf0e0a0bb4727_add (data) {
            geo_json_968e15be879e03eff96cf0e0a0bb4727
                .addData(data);
        }
            geo_json_968e15be879e03eff96cf0e0a0bb4727_add({"features": [{"geometry": {"coordinates": [[-79.607108, 43.821969], [-79.603197, 43.818772], [-79.598943, 43.817264], [-79.595808, 43.817917], [-79.581353, 43.821221], [-79.576334, 43.822241], [-79.568376, 43.823841], [-79.563054, 43.824944], [-79.5554, 43.826123], [-79.551817, 43.826688], [-79.539777, 43.829052], [-79.536258, 43.829826], [-79.533053, 43.830632], [-79.53213, 43.827908], [-79.533949, 43.827009], [-79.532409, 43.830627], [-79.52681, 43.832303], [-79.522334, 43.833247], [-79.517633, 43.834339], [-79.51401, 43.83509], [-79.50858, 43.836217], [-79.506422, 43.836717], [-79.502653, 43.838176], [-79.49967, 43.838683], [-79.499936, 43.838986], [-79.492587, 43.840558], [-79.487236, 43.841654], [-79.483409, 43.842449], [-79.47708, 43.843803], [-79.470598, 43.845105], [-79.462243, 43.846805], [-79.459176, 43.847478], [-79.453336, 43.848699], [-79.448581, 43.849655], [-79.445704, 43.850264], [-79.440159, 43.851441], [-79.435673, 43.852371], [-79.433448, 43.852814], [-79.431741, 43.853213], [-79.425889, 43.85461], [-79.423976, 43.854918], [-79.421689, 43.855354], [-79.416426, 43.856521], [-79.411293, 43.857634], [-79.403154, 43.858649], [-79.396414, 43.860144], [-79.389549, 43.861649], [-79.387236, 43.862243], [-79.384401, 43.862976], [-79.382504, 43.865499], [-79.385611, 43.867234]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_968e15be879e03eff96cf0e0a0bb4727.bindTooltip(
                `<div>
                     85 RUTHERFORD
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_968e15be879e03eff96cf0e0a0bb4727.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_efdc6deca4a17cea4924f4552b8e38a0_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3238E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_efdc6deca4a17cea4924f4552b8e38a0_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_efdc6deca4a17cea4924f4552b8e38a0 = L.geoJson(null, {
                onEachFeature: geo_json_efdc6deca4a17cea4924f4552b8e38a0_onEachFeature,
            
                style: geo_json_efdc6deca4a17cea4924f4552b8e38a0_styler,
            ...{
}
        });

        function geo_json_efdc6deca4a17cea4924f4552b8e38a0_add (data) {
            geo_json_efdc6deca4a17cea4924f4552b8e38a0
                .addData(data);
        }
            geo_json_efdc6deca4a17cea4924f4552b8e38a0_add({"features": [{"geometry": {"coordinates": [[-79.385611, 43.867234], [-79.386453, 43.869696], [-79.387789, 43.865758], [-79.387151, 43.862688], [-79.390447, 43.86172], [-79.395588, 43.860576], [-79.40249, 43.859024], [-79.410677, 43.858001], [-79.416038, 43.856802], [-79.421105, 43.855699], [-79.423587, 43.855157], [-79.425478, 43.854879], [-79.43261, 43.85327], [-79.43634, 43.852438], [-79.439784, 43.851728], [-79.445248, 43.850635], [-79.448837, 43.849832], [-79.453123, 43.848964], [-79.455343, 43.8485], [-79.458275, 43.84789], [-79.46167, 43.847164], [-79.469857, 43.84546], [-79.47304, 43.844851], [-79.476325, 43.844183], [-79.482569, 43.84286], [-79.486606, 43.842052], [-79.491921, 43.840926], [-79.49967, 43.838683], [-79.502092, 43.838655], [-79.507436, 43.836714], [-79.513541, 43.835411], [-79.517067, 43.834686], [-79.521677, 43.833661], [-79.526454, 43.832629], [-79.53213, 43.827908], [-79.534178, 43.827276], [-79.538856, 43.829518], [-79.542212, 43.828887], [-79.55202, 43.826906], [-79.555823, 43.826346], [-79.562378, 43.825296], [-79.567447, 43.824281], [-79.575635, 43.82264], [-79.58189, 43.821335], [-79.595246, 43.818276], [-79.600164, 43.817235], [-79.601983, 43.816775], [-79.605667, 43.81591], [-79.610958, 43.814749], [-79.616104, 43.81353], [-79.616569, 43.813884], [-79.618076, 43.814864], [-79.620676, 43.814527], [-79.623266, 43.815483], [-79.62513, 43.81722], [-79.625605, 43.819785], [-79.624827, 43.821181], [-79.622131, 43.822577], [-79.620199, 43.822973], [-79.617296, 43.823517], [-79.614259, 43.824148], [-79.611034, 43.825414], [-79.609719, 43.825861], [-79.608323, 43.824053], [-79.607108, 43.821969]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_efdc6deca4a17cea4924f4552b8e38a0.bindTooltip(
                `<div>
                     85 RUTHERFORD
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_efdc6deca4a17cea4924f4552b8e38a0.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_927c4d7e1ed1aa135cdb697ae7e8d2e1_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3238E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_927c4d7e1ed1aa135cdb697ae7e8d2e1_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_927c4d7e1ed1aa135cdb697ae7e8d2e1 = L.geoJson(null, {
                onEachFeature: geo_json_927c4d7e1ed1aa135cdb697ae7e8d2e1_onEachFeature,
            
                style: geo_json_927c4d7e1ed1aa135cdb697ae7e8d2e1_styler,
            ...{
}
        });

        function geo_json_927c4d7e1ed1aa135cdb697ae7e8d2e1_add (data) {
            geo_json_927c4d7e1ed1aa135cdb697ae7e8d2e1
                .addData(data);
        }
            geo_json_927c4d7e1ed1aa135cdb697ae7e8d2e1_add({"features": [{"geometry": {"coordinates": [[-79.43261, 43.85327], [-79.43634, 43.852438], [-79.439784, 43.851728], [-79.445248, 43.850635], [-79.448837, 43.849832], [-79.453123, 43.848964], [-79.455343, 43.8485], [-79.458275, 43.84789], [-79.46167, 43.847164], [-79.469857, 43.84546], [-79.47304, 43.844851], [-79.476325, 43.844183], [-79.482569, 43.84286], [-79.486606, 43.842052], [-79.491921, 43.840926], [-79.500233, 43.839244], [-79.502092, 43.838655], [-79.507436, 43.836714], [-79.513541, 43.835411], [-79.517067, 43.834686], [-79.521677, 43.833661], [-79.526454, 43.832629], [-79.53213, 43.827908], [-79.534178, 43.827276], [-79.538856, 43.829518], [-79.542212, 43.828887], [-79.55202, 43.826906], [-79.555823, 43.826346], [-79.562378, 43.825296], [-79.567447, 43.824281], [-79.575635, 43.82264], [-79.58189, 43.821335], [-79.595246, 43.818276], [-79.600164, 43.817235], [-79.601983, 43.816775], [-79.605667, 43.81591], [-79.610958, 43.814749], [-79.616104, 43.81353], [-79.616569, 43.813884]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_927c4d7e1ed1aa135cdb697ae7e8d2e1.bindTooltip(
                `<div>
                     85 RUTHERFORD
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_927c4d7e1ed1aa135cdb697ae7e8d2e1.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_ebe66b3cb8cfcaa2423f5b96c819b45f_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#B72055", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_ebe66b3cb8cfcaa2423f5b96c819b45f_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_ebe66b3cb8cfcaa2423f5b96c819b45f = L.geoJson(null, {
                onEachFeature: geo_json_ebe66b3cb8cfcaa2423f5b96c819b45f_onEachFeature,
            
                style: geo_json_ebe66b3cb8cfcaa2423f5b96c819b45f_styler,
            ...{
}
        });

        function geo_json_ebe66b3cb8cfcaa2423f5b96c819b45f_add (data) {
            geo_json_ebe66b3cb8cfcaa2423f5b96c819b45f
                .addData(data);
        }
            geo_json_ebe66b3cb8cfcaa2423f5b96c819b45f_add({"features": [{"geometry": {"coordinates": [[-79.425301, 43.83968], [-79.422889, 43.841795], [-79.424129, 43.843914], [-79.42455, 43.845371], [-79.426378, 43.848433], [-79.427291, 43.852045], [-79.426438, 43.85427], [-79.43261, 43.85327], [-79.432974, 43.853602], [-79.43334, 43.855265], [-79.434036, 43.858256], [-79.434437, 43.860022], [-79.432577, 43.860876], [-79.431353, 43.863215], [-79.42719, 43.865793], [-79.421829, 43.866976], [-79.423149, 43.868726], [-79.423566, 43.870179], [-79.423708, 43.872041], [-79.424479, 43.873902], [-79.425623, 43.877612], [-79.426708, 43.879746], [-79.429176, 43.882201], [-79.430758, 43.884104], [-79.431853, 43.886765], [-79.432069, 43.889079], [-79.431345, 43.891294], [-79.436046, 43.890895], [-79.438204, 43.890483], [-79.4412, 43.889828], [-79.441423, 43.890207], [-79.442098, 43.894543], [-79.439046, 43.895895], [-79.4393, 43.899319], [-79.440369, 43.902767], [-79.440836, 43.905496], [-79.43702, 43.904954], [-79.434867, 43.904903], [-79.432126, 43.906044], [-79.432716, 43.908117], [-79.43462, 43.909926], [-79.432, 43.911563], [-79.432502, 43.913008], [-79.435952, 43.913066]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_ebe66b3cb8cfcaa2423f5b96c819b45f.bindTooltip(
                `<div>
                     86 NEWKIRK - RED MAPLE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_ebe66b3cb8cfcaa2423f5b96c819b45f.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_3aeaa62599ebb756e91a7cd92e5e7a57_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#B72055", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_3aeaa62599ebb756e91a7cd92e5e7a57_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_3aeaa62599ebb756e91a7cd92e5e7a57 = L.geoJson(null, {
                onEachFeature: geo_json_3aeaa62599ebb756e91a7cd92e5e7a57_onEachFeature,
            
                style: geo_json_3aeaa62599ebb756e91a7cd92e5e7a57_styler,
            ...{
}
        });

        function geo_json_3aeaa62599ebb756e91a7cd92e5e7a57_add (data) {
            geo_json_3aeaa62599ebb756e91a7cd92e5e7a57
                .addData(data);
        }
            geo_json_3aeaa62599ebb756e91a7cd92e5e7a57_add({"features": [{"geometry": {"coordinates": [[-79.435952, 43.913066], [-79.43706, 43.916375], [-79.43481, 43.916803], [-79.433112, 43.915613], [-79.43276, 43.913428], [-79.432265, 43.912081], [-79.434518, 43.909347], [-79.432869, 43.908081], [-79.432208, 43.906514], [-79.43467, 43.905058], [-79.436588, 43.904813], [-79.440859, 43.905785], [-79.440169, 43.901903], [-79.439569, 43.899734], [-79.439356, 43.896475], [-79.439173, 43.895565], [-79.442098, 43.894543], [-79.439307, 43.89525], [-79.438904, 43.893018], [-79.438924, 43.891238], [-79.435962, 43.890746], [-79.4315, 43.891677], [-79.43229, 43.88932], [-79.432011, 43.88674], [-79.430865, 43.883931], [-79.429694, 43.882435], [-79.426724, 43.879554], [-79.425959, 43.877914], [-79.424949, 43.874498], [-79.423969, 43.872394], [-79.423221, 43.870551], [-79.423154, 43.868391], [-79.421753, 43.867163], [-79.427487, 43.865813], [-79.431412, 43.863691], [-79.433227, 43.860684], [-79.434583, 43.858768], [-79.433883, 43.855794], [-79.431741, 43.853213], [-79.425889, 43.85461], [-79.427516, 43.852239], [-79.426747, 43.850352], [-79.426164, 43.847594], [-79.424851, 43.84581], [-79.424281, 43.843877], [-79.423529, 43.842359], [-79.422957, 43.841393], [-79.421021, 43.839908], [-79.425301, 43.83968]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_3aeaa62599ebb756e91a7cd92e5e7a57.bindTooltip(
                `<div>
                     86 NEWKIRK - RED MAPLE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_3aeaa62599ebb756e91a7cd92e5e7a57.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_baf1b82639b6fab204cdea170a38c977_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#B72055", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_baf1b82639b6fab204cdea170a38c977_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_baf1b82639b6fab204cdea170a38c977 = L.geoJson(null, {
                onEachFeature: geo_json_baf1b82639b6fab204cdea170a38c977_onEachFeature,
            
                style: geo_json_baf1b82639b6fab204cdea170a38c977_styler,
            ...{
}
        });

        function geo_json_baf1b82639b6fab204cdea170a38c977_add (data) {
            geo_json_baf1b82639b6fab204cdea170a38c977
                .addData(data);
        }
            geo_json_baf1b82639b6fab204cdea170a38c977_add({"features": [{"geometry": {"coordinates": [[-79.425301, 43.83968], [-79.422889, 43.841795], [-79.424129, 43.843914], [-79.42455, 43.845371], [-79.426378, 43.848433], [-79.427291, 43.852045], [-79.426438, 43.85427], [-79.43261, 43.85327], [-79.432974, 43.853602], [-79.43334, 43.855265], [-79.434036, 43.858256], [-79.434437, 43.860022], [-79.432577, 43.860876], [-79.431353, 43.863215], [-79.42719, 43.865793], [-79.421829, 43.866976], [-79.423149, 43.868726], [-79.423566, 43.870179], [-79.423708, 43.872041], [-79.424479, 43.873902], [-79.426188, 43.875888], [-79.425623, 43.877612], [-79.426708, 43.879746], [-79.429176, 43.882201], [-79.430758, 43.884104], [-79.431853, 43.886765], [-79.432069, 43.889079], [-79.431345, 43.891294], [-79.436046, 43.890895], [-79.438204, 43.890483], [-79.4412, 43.889828], [-79.441423, 43.890207], [-79.442098, 43.894543], [-79.439046, 43.895895], [-79.4393, 43.899319], [-79.440369, 43.902767], [-79.440836, 43.905496], [-79.43702, 43.904954], [-79.434867, 43.904903], [-79.432126, 43.906044], [-79.432716, 43.908117], [-79.43462, 43.909926], [-79.432, 43.911563], [-79.432502, 43.913008], [-79.435952, 43.913066]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_baf1b82639b6fab204cdea170a38c977.bindTooltip(
                `<div>
                     86 NEWKIRK - RED MAPLE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_baf1b82639b6fab204cdea170a38c977.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_1cdea45a93e657df0792f7dfc9190b0b_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#B72055", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_1cdea45a93e657df0792f7dfc9190b0b_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_1cdea45a93e657df0792f7dfc9190b0b = L.geoJson(null, {
                onEachFeature: geo_json_1cdea45a93e657df0792f7dfc9190b0b_onEachFeature,
            
                style: geo_json_1cdea45a93e657df0792f7dfc9190b0b_styler,
            ...{
}
        });

        function geo_json_1cdea45a93e657df0792f7dfc9190b0b_add (data) {
            geo_json_1cdea45a93e657df0792f7dfc9190b0b
                .addData(data);
        }
            geo_json_1cdea45a93e657df0792f7dfc9190b0b_add({"features": [{"geometry": {"coordinates": [[-79.425301, 43.83968], [-79.422889, 43.841795], [-79.424129, 43.843914], [-79.42455, 43.845371], [-79.426378, 43.848433], [-79.427291, 43.852045], [-79.426438, 43.85427], [-79.43261, 43.85327], [-79.432974, 43.853602], [-79.43334, 43.855265], [-79.434036, 43.858256], [-79.434437, 43.860022], [-79.432577, 43.860876], [-79.431353, 43.863215], [-79.42719, 43.865793], [-79.421829, 43.866976], [-79.423149, 43.868726], [-79.423566, 43.870179], [-79.423708, 43.872041], [-79.424479, 43.873902], [-79.426188, 43.875888], [-79.425623, 43.877612], [-79.426708, 43.879746], [-79.429176, 43.882201], [-79.430758, 43.884104], [-79.431853, 43.886765], [-79.432069, 43.889079], [-79.431345, 43.891294], [-79.436046, 43.890895], [-79.438204, 43.890483], [-79.4412, 43.889828], [-79.441423, 43.890207], [-79.442098, 43.894543], [-79.439046, 43.895895], [-79.4393, 43.899319], [-79.440369, 43.902767], [-79.440836, 43.905496], [-79.43702, 43.904954], [-79.434867, 43.904903], [-79.432126, 43.906044], [-79.432716, 43.908117], [-79.43462, 43.909926], [-79.432, 43.911563], [-79.432502, 43.913008], [-79.435952, 43.913066], [-79.43706, 43.916375], [-79.43481, 43.916803], [-79.433112, 43.915613], [-79.43276, 43.913428]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_1cdea45a93e657df0792f7dfc9190b0b.bindTooltip(
                `<div>
                     86 NEWKIRK - RED MAPLE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_1cdea45a93e657df0792f7dfc9190b0b.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_0f71c1001a36869ae84f8d1f8f7a1b84_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#B72055", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_0f71c1001a36869ae84f8d1f8f7a1b84_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_0f71c1001a36869ae84f8d1f8f7a1b84 = L.geoJson(null, {
                onEachFeature: geo_json_0f71c1001a36869ae84f8d1f8f7a1b84_onEachFeature,
            
                style: geo_json_0f71c1001a36869ae84f8d1f8f7a1b84_styler,
            ...{
}
        });

        function geo_json_0f71c1001a36869ae84f8d1f8f7a1b84_add (data) {
            geo_json_0f71c1001a36869ae84f8d1f8f7a1b84
                .addData(data);
        }
            geo_json_0f71c1001a36869ae84f8d1f8f7a1b84_add({"features": [{"geometry": {"coordinates": [[-79.425301, 43.83968], [-79.422889, 43.841795], [-79.424129, 43.843914], [-79.42455, 43.845371], [-79.426378, 43.848433], [-79.427291, 43.852045], [-79.426438, 43.85427], [-79.43261, 43.85327], [-79.432974, 43.853602], [-79.43334, 43.855265], [-79.434036, 43.858256], [-79.434437, 43.860022], [-79.432577, 43.860876], [-79.431353, 43.863215], [-79.42719, 43.865793], [-79.421829, 43.866976], [-79.423149, 43.868726], [-79.423566, 43.870179], [-79.423708, 43.872041], [-79.424479, 43.873902], [-79.425623, 43.877612], [-79.421787, 43.878546], [-79.416943, 43.882699], [-79.418293, 43.885157], [-79.422634, 43.884188], [-79.425659, 43.883561], [-79.430758, 43.884104], [-79.431853, 43.886765], [-79.432069, 43.889079], [-79.431345, 43.891294], [-79.436046, 43.890895], [-79.438204, 43.890483], [-79.4412, 43.889828], [-79.441423, 43.890207], [-79.442098, 43.894543], [-79.439046, 43.895895], [-79.4393, 43.899319], [-79.440369, 43.902767], [-79.440836, 43.905496], [-79.43702, 43.904954], [-79.434867, 43.904903], [-79.432126, 43.906044], [-79.432716, 43.908117], [-79.43462, 43.909926], [-79.432, 43.911563], [-79.432502, 43.913008], [-79.435952, 43.913066]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_0f71c1001a36869ae84f8d1f8f7a1b84.bindTooltip(
                `<div>
                     86 NEWKIRK - RED MAPLE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_0f71c1001a36869ae84f8d1f8f7a1b84.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_6e36d6533a7217626785e990dc785b0e_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#B72055", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_6e36d6533a7217626785e990dc785b0e_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_6e36d6533a7217626785e990dc785b0e = L.geoJson(null, {
                onEachFeature: geo_json_6e36d6533a7217626785e990dc785b0e_onEachFeature,
            
                style: geo_json_6e36d6533a7217626785e990dc785b0e_styler,
            ...{
}
        });

        function geo_json_6e36d6533a7217626785e990dc785b0e_add (data) {
            geo_json_6e36d6533a7217626785e990dc785b0e
                .addData(data);
        }
            geo_json_6e36d6533a7217626785e990dc785b0e_add({"features": [{"geometry": {"coordinates": [[-79.435952, 43.913066], [-79.43706, 43.916375], [-79.43481, 43.916803], [-79.433112, 43.915613], [-79.43276, 43.913428], [-79.432265, 43.912081], [-79.434518, 43.909347], [-79.432869, 43.908081], [-79.432208, 43.906514], [-79.43467, 43.905058], [-79.436588, 43.904813], [-79.440859, 43.905785], [-79.440169, 43.901903], [-79.439569, 43.899734], [-79.439356, 43.896475], [-79.439173, 43.895565], [-79.442098, 43.894543], [-79.439307, 43.89525], [-79.438904, 43.893018], [-79.438924, 43.891238], [-79.435962, 43.890746], [-79.4315, 43.891677], [-79.43229, 43.88932], [-79.432011, 43.88674], [-79.430865, 43.883931], [-79.429694, 43.882435], [-79.426724, 43.879554], [-79.425959, 43.877914], [-79.426188, 43.875888], [-79.424949, 43.874498], [-79.423969, 43.872394], [-79.423221, 43.870551], [-79.423154, 43.868391], [-79.421753, 43.867163], [-79.427487, 43.865813], [-79.431412, 43.863691], [-79.433227, 43.860684], [-79.434583, 43.858768], [-79.433883, 43.855794], [-79.431741, 43.853213], [-79.425889, 43.85461], [-79.427516, 43.852239], [-79.426747, 43.850352], [-79.426164, 43.847594], [-79.424851, 43.84581], [-79.424281, 43.843877], [-79.423529, 43.842359], [-79.422957, 43.841393], [-79.421021, 43.839908], [-79.425301, 43.83968]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_6e36d6533a7217626785e990dc785b0e.bindTooltip(
                `<div>
                     86 NEWKIRK - RED MAPLE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_6e36d6533a7217626785e990dc785b0e.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_16044dba0beb3a998c489d6620c1b004_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#B72055", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_16044dba0beb3a998c489d6620c1b004_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_16044dba0beb3a998c489d6620c1b004 = L.geoJson(null, {
                onEachFeature: geo_json_16044dba0beb3a998c489d6620c1b004_onEachFeature,
            
                style: geo_json_16044dba0beb3a998c489d6620c1b004_styler,
            ...{
}
        });

        function geo_json_16044dba0beb3a998c489d6620c1b004_add (data) {
            geo_json_16044dba0beb3a998c489d6620c1b004
                .addData(data);
        }
            geo_json_16044dba0beb3a998c489d6620c1b004_add({"features": [{"geometry": {"coordinates": [[-79.435952, 43.913066], [-79.43706, 43.916375], [-79.43481, 43.916803], [-79.433112, 43.915613], [-79.43276, 43.913428], [-79.432265, 43.912081], [-79.434518, 43.909347], [-79.432869, 43.908081], [-79.432208, 43.906514], [-79.43467, 43.905058], [-79.436588, 43.904813], [-79.440859, 43.905785], [-79.440169, 43.901903], [-79.439569, 43.899734], [-79.439356, 43.896475], [-79.439173, 43.895565], [-79.442098, 43.894543], [-79.439307, 43.89525], [-79.438904, 43.893018], [-79.438924, 43.891238], [-79.435962, 43.890746], [-79.4315, 43.891677], [-79.43229, 43.88932], [-79.432011, 43.88674], [-79.430865, 43.883931], [-79.428701, 43.882548], [-79.425803, 43.883392], [-79.422847, 43.884053], [-79.417967, 43.885105], [-79.417259, 43.882953], [-79.416569, 43.880167], [-79.421499, 43.878696], [-79.424949, 43.874498], [-79.423969, 43.872394], [-79.423221, 43.870551], [-79.423154, 43.868391], [-79.421753, 43.867163], [-79.427487, 43.865813], [-79.431412, 43.863691], [-79.433227, 43.860684], [-79.434583, 43.858768], [-79.433883, 43.855794], [-79.431741, 43.853213], [-79.425889, 43.85461], [-79.427516, 43.852239], [-79.426747, 43.850352], [-79.426164, 43.847594], [-79.424851, 43.84581], [-79.424281, 43.843877], [-79.423529, 43.842359], [-79.422957, 43.841393], [-79.421021, 43.839908], [-79.425301, 43.83968]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_16044dba0beb3a998c489d6620c1b004.bindTooltip(
                `<div>
                     86 NEWKIRK - RED MAPLE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_16044dba0beb3a998c489d6620c1b004.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_da514dbb6aa345f823395a49807614c6_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#B72055", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_da514dbb6aa345f823395a49807614c6_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_da514dbb6aa345f823395a49807614c6 = L.geoJson(null, {
                onEachFeature: geo_json_da514dbb6aa345f823395a49807614c6_onEachFeature,
            
                style: geo_json_da514dbb6aa345f823395a49807614c6_styler,
            ...{
}
        });

        function geo_json_da514dbb6aa345f823395a49807614c6_add (data) {
            geo_json_da514dbb6aa345f823395a49807614c6
                .addData(data);
        }
            geo_json_da514dbb6aa345f823395a49807614c6_add({"features": [{"geometry": {"coordinates": [[-79.425301, 43.83968], [-79.422889, 43.841795], [-79.424129, 43.843914], [-79.42455, 43.845371], [-79.426378, 43.848433], [-79.427291, 43.852045], [-79.426438, 43.85427], [-79.43261, 43.85327], [-79.432974, 43.853602], [-79.43334, 43.855265], [-79.434036, 43.858256], [-79.434437, 43.860022], [-79.432577, 43.860876], [-79.431353, 43.863215], [-79.42719, 43.865793], [-79.421829, 43.866976], [-79.423149, 43.868726], [-79.423566, 43.870179], [-79.423708, 43.872041], [-79.424479, 43.873902], [-79.425623, 43.877612], [-79.426708, 43.879746], [-79.429176, 43.882201], [-79.430758, 43.884104], [-79.431853, 43.886765], [-79.432069, 43.889079], [-79.431345, 43.891294], [-79.436046, 43.890895], [-79.438204, 43.890483], [-79.4412, 43.889828], [-79.441423, 43.890207], [-79.442098, 43.894543], [-79.439046, 43.895895], [-79.4393, 43.899319], [-79.440369, 43.902767], [-79.440836, 43.905496], [-79.43702, 43.904954], [-79.434867, 43.904903], [-79.432126, 43.906044], [-79.432716, 43.908117], [-79.43462, 43.909926], [-79.432, 43.911563], [-79.432502, 43.913008], [-79.435952, 43.913066], [-79.43706, 43.916375], [-79.43481, 43.916803], [-79.433112, 43.915613], [-79.43276, 43.913428]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_da514dbb6aa345f823395a49807614c6.bindTooltip(
                `<div>
                     86 NEWKIRK - RED MAPLE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_da514dbb6aa345f823395a49807614c6.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_5bd02315a772d32cda1515bb14694ee7_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#C4A006", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_5bd02315a772d32cda1515bb14694ee7_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_5bd02315a772d32cda1515bb14694ee7 = L.geoJson(null, {
                onEachFeature: geo_json_5bd02315a772d32cda1515bb14694ee7_onEachFeature,
            
                style: geo_json_5bd02315a772d32cda1515bb14694ee7_styler,
            ...{
}
        });

        function geo_json_5bd02315a772d32cda1515bb14694ee7_add (data) {
            geo_json_5bd02315a772d32cda1515bb14694ee7
                .addData(data);
        }
            geo_json_5bd02315a772d32cda1515bb14694ee7_add({"features": [{"geometry": {"coordinates": [[-79.53437, 43.827187], [-79.532409, 43.830627], [-79.52681, 43.832303], [-79.522334, 43.833247], [-79.517633, 43.834339], [-79.51401, 43.83509], [-79.50858, 43.836217], [-79.506422, 43.836717], [-79.502653, 43.838176], [-79.499377, 43.838647], [-79.492587, 43.840558], [-79.491651, 43.837798], [-79.492202, 43.83639], [-79.488069, 43.835275], [-79.485614, 43.835276], [-79.481691, 43.83573], [-79.478157, 43.836269], [-79.475465, 43.836556], [-79.471865, 43.836374], [-79.468658, 43.835673], [-79.465879, 43.835956], [-79.462367, 43.836336], [-79.457447, 43.836834], [-79.45568, 43.834475], [-79.440029, 43.833162], [-79.440445, 43.834282], [-79.441342, 43.836684], [-79.436545, 43.837812], [-79.430101, 43.8391], [-79.42546, 43.839813]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_5bd02315a772d32cda1515bb14694ee7.bindTooltip(
                `<div>
                     87 AUTUMN HILL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_5bd02315a772d32cda1515bb14694ee7.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_5f06cef4183e3cd61a9845326fde1606_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#C4A006", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_5f06cef4183e3cd61a9845326fde1606_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_5f06cef4183e3cd61a9845326fde1606 = L.geoJson(null, {
                onEachFeature: geo_json_5f06cef4183e3cd61a9845326fde1606_onEachFeature,
            
                style: geo_json_5f06cef4183e3cd61a9845326fde1606_styler,
            ...{
}
        });

        function geo_json_5f06cef4183e3cd61a9845326fde1606_add (data) {
            geo_json_5f06cef4183e3cd61a9845326fde1606
                .addData(data);
        }
            geo_json_5f06cef4183e3cd61a9845326fde1606_add({"features": [{"geometry": {"coordinates": [[-79.42546, 43.839813], [-79.430269, 43.839232], [-79.436214, 43.837963], [-79.439183, 43.837347], [-79.441343, 43.836112], [-79.440651, 43.83448], [-79.439924, 43.83268], [-79.454793, 43.832875], [-79.455218, 43.834045], [-79.457728, 43.836948], [-79.463244, 43.836346], [-79.466166, 43.836018], [-79.471802, 43.836479], [-79.475037, 43.83669], [-79.477867, 43.836394], [-79.481169, 43.835943], [-79.482683, 43.835804], [-79.48499, 43.835346], [-79.488109, 43.835348], [-79.492102, 43.836061], [-79.491583, 43.83729], [-79.491953, 43.840146], [-79.499377, 43.838647], [-79.502092, 43.838655], [-79.507436, 43.836714], [-79.513541, 43.835411], [-79.517067, 43.834686], [-79.521677, 43.833661], [-79.526454, 43.832629], [-79.53213, 43.827908], [-79.53437, 43.827187]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_5f06cef4183e3cd61a9845326fde1606.bindTooltip(
                `<div>
                     87 AUTUMN HILL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_5f06cef4183e3cd61a9845326fde1606.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_072d96e9cb029d07cf46b59ce6aeb15e_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00A88E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_072d96e9cb029d07cf46b59ce6aeb15e_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_072d96e9cb029d07cf46b59ce6aeb15e = L.geoJson(null, {
                onEachFeature: geo_json_072d96e9cb029d07cf46b59ce6aeb15e_onEachFeature,
            
                style: geo_json_072d96e9cb029d07cf46b59ce6aeb15e_styler,
            ...{
}
        });

        function geo_json_072d96e9cb029d07cf46b59ce6aeb15e_add (data) {
            geo_json_072d96e9cb029d07cf46b59ce6aeb15e
                .addData(data);
        }
            geo_json_072d96e9cb029d07cf46b59ce6aeb15e_add({"features": [{"geometry": {"coordinates": [[-79.414881, 43.782516], [-79.416698, 43.78496], [-79.417335, 43.787532], [-79.417977, 43.790138], [-79.418316, 43.79149], [-79.418994, 43.794272], [-79.42067, 43.79802], [-79.424712, 43.797159], [-79.429061, 43.796213], [-79.432411, 43.795398], [-79.436374, 43.794536], [-79.440814, 43.793578], [-79.44571, 43.793017], [-79.445951, 43.794066], [-79.446676, 43.796784], [-79.447251, 43.799275], [-79.448198, 43.803249], [-79.450141, 43.807584], [-79.454291, 43.809406], [-79.45019, 43.81265], [-79.450745, 43.814571], [-79.451357, 43.81695], [-79.452742, 43.822771], [-79.454793, 43.832875], [-79.455218, 43.834045], [-79.456035, 43.836976], [-79.456868, 43.839874], [-79.457504, 43.843209], [-79.457913, 43.844992], [-79.458459, 43.847506], [-79.459409, 43.851565], [-79.460097, 43.854737], [-79.46062, 43.856893], [-79.461102, 43.858969], [-79.461653, 43.861501], [-79.46246, 43.865309], [-79.464272, 43.873016], [-79.465698, 43.877933], [-79.466533, 43.881353], [-79.467146, 43.883944], [-79.468179, 43.888451], [-79.469466, 43.893874], [-79.471589, 43.902252], [-79.472561, 43.906114], [-79.473346, 43.909434], [-79.474197, 43.913074], [-79.475123, 43.916746], [-79.476003, 43.919624], [-79.478508, 43.928001], [-79.479309, 43.931197], [-79.480246, 43.934876], [-79.480794, 43.937106], [-79.481127, 43.938188], [-79.481847, 43.941297], [-79.482606, 43.944245], [-79.482987, 43.946731], [-79.483725, 43.950328], [-79.484461, 43.953387], [-79.485222, 43.956773], [-79.491352, 43.956272], [-79.502292, 43.953787], [-79.508964, 43.95229], [-79.519164, 43.954713]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_072d96e9cb029d07cf46b59ce6aeb15e.bindTooltip(
                `<div>
                     88 BATHURST
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_072d96e9cb029d07cf46b59ce6aeb15e.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_e84df5b17eceb3448e96dfbe97f99611_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00A88E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_e84df5b17eceb3448e96dfbe97f99611_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_e84df5b17eceb3448e96dfbe97f99611 = L.geoJson(null, {
                onEachFeature: geo_json_e84df5b17eceb3448e96dfbe97f99611_onEachFeature,
            
                style: geo_json_e84df5b17eceb3448e96dfbe97f99611_styler,
            ...{
}
        });

        function geo_json_e84df5b17eceb3448e96dfbe97f99611_add (data) {
            geo_json_e84df5b17eceb3448e96dfbe97f99611
                .addData(data);
        }
            geo_json_e84df5b17eceb3448e96dfbe97f99611_add({"features": [{"geometry": {"coordinates": [[-79.454291, 43.809406], [-79.45019, 43.81265], [-79.450745, 43.814571], [-79.451357, 43.81695], [-79.452742, 43.822771], [-79.454793, 43.832875], [-79.455218, 43.834045], [-79.456035, 43.836976], [-79.456868, 43.839874], [-79.457504, 43.843209], [-79.457913, 43.844992], [-79.458459, 43.847506], [-79.459409, 43.851565], [-79.460097, 43.854737], [-79.46062, 43.856893], [-79.461102, 43.858969], [-79.461653, 43.861501], [-79.46246, 43.865309], [-79.464272, 43.873016], [-79.465698, 43.877933], [-79.466533, 43.881353], [-79.467146, 43.883944], [-79.468179, 43.888451], [-79.469466, 43.893874], [-79.471589, 43.902252], [-79.472561, 43.906114], [-79.473346, 43.909434], [-79.474197, 43.913074], [-79.475123, 43.916746], [-79.476003, 43.919624], [-79.478508, 43.928001], [-79.479309, 43.931197], [-79.480246, 43.934876], [-79.480794, 43.937106], [-79.481127, 43.938188], [-79.481847, 43.941297], [-79.482606, 43.944245], [-79.482987, 43.946731], [-79.483725, 43.950328], [-79.484461, 43.953387], [-79.485222, 43.956773], [-79.491352, 43.956272], [-79.502292, 43.953787], [-79.508964, 43.95229], [-79.519164, 43.954713]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_e84df5b17eceb3448e96dfbe97f99611.bindTooltip(
                `<div>
                     88 BATHURST
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_e84df5b17eceb3448e96dfbe97f99611.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_00f478a09d9af7f9f2ab20a01c483e7e_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00A88E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_00f478a09d9af7f9f2ab20a01c483e7e_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_00f478a09d9af7f9f2ab20a01c483e7e = L.geoJson(null, {
                onEachFeature: geo_json_00f478a09d9af7f9f2ab20a01c483e7e_onEachFeature,
            
                style: geo_json_00f478a09d9af7f9f2ab20a01c483e7e_styler,
            ...{
}
        });

        function geo_json_00f478a09d9af7f9f2ab20a01c483e7e_add (data) {
            geo_json_00f478a09d9af7f9f2ab20a01c483e7e
                .addData(data);
        }
            geo_json_00f478a09d9af7f9f2ab20a01c483e7e_add({"features": [{"geometry": {"coordinates": [[-79.519164, 43.954713], [-79.518202, 43.952276], [-79.507987, 43.952388], [-79.501583, 43.953855], [-79.491439, 43.956129], [-79.485864, 43.95734], [-79.484788, 43.953822], [-79.484129, 43.950794], [-79.483406, 43.946924], [-79.482918, 43.944562], [-79.482203, 43.941646], [-79.481647, 43.939099], [-79.480766, 43.935695], [-79.47974, 43.931476], [-79.476895, 43.921082], [-79.47553, 43.917178], [-79.47463, 43.913471], [-79.473783, 43.90998], [-79.472836, 43.906021], [-79.472012, 43.902646], [-79.469887, 43.894326], [-79.467549, 43.884224], [-79.466977, 43.881822], [-79.466163, 43.878471], [-79.464792, 43.873505], [-79.463053, 43.866649], [-79.46208, 43.861909], [-79.460523, 43.855136], [-79.45981, 43.852019], [-79.458877, 43.847892], [-79.458188, 43.845179], [-79.457891, 43.843586], [-79.457311, 43.841016], [-79.456496, 43.837358], [-79.45568, 43.834475], [-79.455129, 43.832302], [-79.453091, 43.822544], [-79.452505, 43.820475], [-79.45187, 43.817555], [-79.451233, 43.814913], [-79.450243, 43.811349], [-79.453986, 43.809727], [-79.45023, 43.810619], [-79.449447, 43.807404], [-79.448472, 43.80293], [-79.447654, 43.79966], [-79.446891, 43.796732], [-79.444574, 43.792606], [-79.441176, 43.793359], [-79.436715, 43.794295], [-79.432926, 43.795135], [-79.429429, 43.795906], [-79.426559, 43.796526], [-79.422779, 43.797323], [-79.420037, 43.797434], [-79.419718, 43.796088], [-79.419191, 43.793992], [-79.418625, 43.791289], [-79.418069, 43.789452], [-79.417496, 43.7872], [-79.414881, 43.782516]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_00f478a09d9af7f9f2ab20a01c483e7e.bindTooltip(
                `<div>
                     88 BATHURST
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_00f478a09d9af7f9f2ab20a01c483e7e.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_0deaadf3070936b56b617aa1b1ed24d5_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00A88E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_0deaadf3070936b56b617aa1b1ed24d5_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_0deaadf3070936b56b617aa1b1ed24d5 = L.geoJson(null, {
                onEachFeature: geo_json_0deaadf3070936b56b617aa1b1ed24d5_onEachFeature,
            
                style: geo_json_0deaadf3070936b56b617aa1b1ed24d5_styler,
            ...{
}
        });

        function geo_json_0deaadf3070936b56b617aa1b1ed24d5_add (data) {
            geo_json_0deaadf3070936b56b617aa1b1ed24d5
                .addData(data);
        }
            geo_json_0deaadf3070936b56b617aa1b1ed24d5_add({"features": [{"geometry": {"coordinates": [[-79.458459, 43.847506], [-79.459409, 43.851565], [-79.460097, 43.854737], [-79.46062, 43.856893], [-79.461102, 43.858969], [-79.461653, 43.861501], [-79.46246, 43.865309], [-79.464272, 43.873016], [-79.465698, 43.877933], [-79.466533, 43.881353], [-79.467146, 43.883944], [-79.468179, 43.888451], [-79.469466, 43.893874], [-79.471589, 43.902252], [-79.472561, 43.906114], [-79.473346, 43.909434], [-79.474197, 43.913074], [-79.475123, 43.916746], [-79.476003, 43.919624], [-79.478508, 43.928001], [-79.479309, 43.931197], [-79.480246, 43.934876], [-79.480794, 43.937106], [-79.481127, 43.938188], [-79.481847, 43.941297], [-79.482606, 43.944245], [-79.482987, 43.946731], [-79.483725, 43.950328], [-79.484461, 43.953387], [-79.485222, 43.956773], [-79.491352, 43.956272], [-79.502292, 43.953787], [-79.508964, 43.95229], [-79.519164, 43.954713]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_0deaadf3070936b56b617aa1b1ed24d5.bindTooltip(
                `<div>
                     88 BATHURST
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_0deaadf3070936b56b617aa1b1ed24d5.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_3083618c7aa804a2d18165ae4d55393e_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00A88E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_3083618c7aa804a2d18165ae4d55393e_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_3083618c7aa804a2d18165ae4d55393e = L.geoJson(null, {
                onEachFeature: geo_json_3083618c7aa804a2d18165ae4d55393e_onEachFeature,
            
                style: geo_json_3083618c7aa804a2d18165ae4d55393e_styler,
            ...{
}
        });

        function geo_json_3083618c7aa804a2d18165ae4d55393e_add (data) {
            geo_json_3083618c7aa804a2d18165ae4d55393e
                .addData(data);
        }
            geo_json_3083618c7aa804a2d18165ae4d55393e_add({"features": [{"geometry": {"coordinates": [[-79.453986, 43.809727], [-79.45023, 43.810619], [-79.449447, 43.807404], [-79.448472, 43.80293], [-79.447654, 43.79966], [-79.446891, 43.796732], [-79.444574, 43.792606], [-79.441176, 43.793359], [-79.436715, 43.794295], [-79.432926, 43.795135], [-79.429429, 43.795906], [-79.426559, 43.796526], [-79.422779, 43.797323], [-79.420037, 43.797434], [-79.419718, 43.796088], [-79.419191, 43.793992], [-79.418625, 43.791289], [-79.418069, 43.789452], [-79.417496, 43.7872], [-79.414881, 43.782516]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_3083618c7aa804a2d18165ae4d55393e.bindTooltip(
                `<div>
                     88 BATHURST
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_3083618c7aa804a2d18165ae4d55393e.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_e07b24bdad957d0dcc6bc3ee97dd6889_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00A88E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_e07b24bdad957d0dcc6bc3ee97dd6889_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_e07b24bdad957d0dcc6bc3ee97dd6889 = L.geoJson(null, {
                onEachFeature: geo_json_e07b24bdad957d0dcc6bc3ee97dd6889_onEachFeature,
            
                style: geo_json_e07b24bdad957d0dcc6bc3ee97dd6889_styler,
            ...{
}
        });

        function geo_json_e07b24bdad957d0dcc6bc3ee97dd6889_add (data) {
            geo_json_e07b24bdad957d0dcc6bc3ee97dd6889
                .addData(data);
        }
            geo_json_e07b24bdad957d0dcc6bc3ee97dd6889_add({"features": [{"geometry": {"coordinates": [[-79.468666, 43.89286], [-79.468936, 43.894405], [-79.467549, 43.884224], [-79.466977, 43.881822], [-79.466163, 43.878471], [-79.464792, 43.873505], [-79.463053, 43.866649], [-79.46208, 43.861909], [-79.460523, 43.855136], [-79.45981, 43.852019], [-79.458877, 43.847892], [-79.458188, 43.845179], [-79.457891, 43.843586], [-79.457311, 43.841016], [-79.456496, 43.837358], [-79.45568, 43.834475], [-79.455129, 43.832302], [-79.453091, 43.822544], [-79.452505, 43.820475], [-79.45187, 43.817555], [-79.451233, 43.814913], [-79.450243, 43.811349], [-79.453986, 43.809727], [-79.45023, 43.810619], [-79.449447, 43.807404], [-79.448472, 43.80293], [-79.447654, 43.79966], [-79.446891, 43.796732], [-79.444574, 43.792606], [-79.441176, 43.793359], [-79.436715, 43.794295], [-79.432926, 43.795135], [-79.429429, 43.795906], [-79.426559, 43.796526], [-79.422779, 43.797323], [-79.420037, 43.797434], [-79.419718, 43.796088], [-79.419191, 43.793992], [-79.418625, 43.791289], [-79.418069, 43.789452], [-79.417496, 43.7872], [-79.414881, 43.782516]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_e07b24bdad957d0dcc6bc3ee97dd6889.bindTooltip(
                `<div>
                     88 BATHURST
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_e07b24bdad957d0dcc6bc3ee97dd6889.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_36eff2a18e0ef293f33474cae7d0e996_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#F58220", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_36eff2a18e0ef293f33474cae7d0e996_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_36eff2a18e0ef293f33474cae7d0e996 = L.geoJson(null, {
                onEachFeature: geo_json_36eff2a18e0ef293f33474cae7d0e996_onEachFeature,
            
                style: geo_json_36eff2a18e0ef293f33474cae7d0e996_styler,
            ...{
}
        });

        function geo_json_36eff2a18e0ef293f33474cae7d0e996_add (data) {
            geo_json_36eff2a18e0ef293f33474cae7d0e996
                .addData(data);
        }
            geo_json_36eff2a18e0ef293f33474cae7d0e996_add({"features": [{"geometry": {"coordinates": [[-79.346338, 43.775808], [-79.34784, 43.777548], [-79.348707, 43.779593], [-79.348945, 43.78272], [-79.350591, 43.7853], [-79.352814, 43.787264], [-79.353993, 43.790176], [-79.354514, 43.792438], [-79.355003, 43.794346], [-79.355097, 43.796288], [-79.354723, 43.797532], [-79.354036, 43.799454], [-79.353236, 43.802438], [-79.354962, 43.805409], [-79.356644, 43.806968], [-79.358763, 43.808857], [-79.360853, 43.81163], [-79.361859, 43.813989], [-79.366706, 43.8192], [-79.369799, 43.822068], [-79.370925, 43.826409], [-79.371997, 43.829491], [-79.377225, 43.831661], [-79.379357, 43.833513], [-79.380956, 43.840048], [-79.381461, 43.841807], [-79.381944, 43.844139], [-79.383111, 43.848278], [-79.384221, 43.852543], [-79.385268, 43.856769], [-79.386068, 43.85951], [-79.386633, 43.861909], [-79.387484, 43.865594], [-79.388258, 43.869131], [-79.389439, 43.873207], [-79.390454, 43.876767], [-79.391327, 43.88034], [-79.392321, 43.885693], [-79.393474, 43.889722], [-79.394446, 43.893655], [-79.394941, 43.895489], [-79.395602, 43.898378], [-79.393049, 43.901698], [-79.395767, 43.903735], [-79.396565, 43.900932]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_36eff2a18e0ef293f33474cae7d0e996.bindTooltip(
                `<div>
                     90 LESLIE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_36eff2a18e0ef293f33474cae7d0e996.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_026a6d07969ea4d05347d81b9b72fb5c_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#F58220", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_026a6d07969ea4d05347d81b9b72fb5c_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_026a6d07969ea4d05347d81b9b72fb5c = L.geoJson(null, {
                onEachFeature: geo_json_026a6d07969ea4d05347d81b9b72fb5c_onEachFeature,
            
                style: geo_json_026a6d07969ea4d05347d81b9b72fb5c_styler,
            ...{
}
        });

        function geo_json_026a6d07969ea4d05347d81b9b72fb5c_add (data) {
            geo_json_026a6d07969ea4d05347d81b9b72fb5c
                .addData(data);
        }
            geo_json_026a6d07969ea4d05347d81b9b72fb5c_add({"features": [{"geometry": {"coordinates": [[-79.381944, 43.844139], [-79.383111, 43.848278], [-79.384221, 43.852543], [-79.385268, 43.856769], [-79.386068, 43.85951], [-79.386633, 43.861909], [-79.387484, 43.865594], [-79.388258, 43.869131], [-79.389439, 43.873207], [-79.390454, 43.876767], [-79.391327, 43.88034], [-79.392321, 43.885693], [-79.393474, 43.889722], [-79.394446, 43.893655], [-79.394941, 43.895489], [-79.395602, 43.898378], [-79.393049, 43.901698], [-79.395767, 43.903735], [-79.396565, 43.900932]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_026a6d07969ea4d05347d81b9b72fb5c.bindTooltip(
                `<div>
                     90 LESLIE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_026a6d07969ea4d05347d81b9b72fb5c.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_8ae617e7d7c877f89bc6583980a922d6_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#F58220", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_8ae617e7d7c877f89bc6583980a922d6_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_8ae617e7d7c877f89bc6583980a922d6 = L.geoJson(null, {
                onEachFeature: geo_json_8ae617e7d7c877f89bc6583980a922d6_onEachFeature,
            
                style: geo_json_8ae617e7d7c877f89bc6583980a922d6_styler,
            ...{
}
        });

        function geo_json_8ae617e7d7c877f89bc6583980a922d6_add (data) {
            geo_json_8ae617e7d7c877f89bc6583980a922d6
                .addData(data);
        }
            geo_json_8ae617e7d7c877f89bc6583980a922d6_add({"features": [{"geometry": {"coordinates": [[-79.382563, 43.844713], [-79.381863, 43.842087], [-79.381062, 43.838835], [-79.379788, 43.833875], [-79.375664, 43.831165], [-79.372032, 43.829082], [-79.371314, 43.826734], [-79.369937, 43.82163], [-79.367274, 43.819227], [-79.362201, 43.814192], [-79.361138, 43.811731], [-79.35924, 43.809063], [-79.357016, 43.807101], [-79.354906, 43.805007], [-79.353481, 43.802539], [-79.354216, 43.799793], [-79.354822, 43.798001], [-79.355294, 43.796564], [-79.354963, 43.792903], [-79.354292, 43.790394], [-79.353216, 43.787472], [-79.353032, 43.78402], [-79.35234, 43.782346], [-79.345935, 43.779576], [-79.34506, 43.775683]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_8ae617e7d7c877f89bc6583980a922d6.bindTooltip(
                `<div>
                     90 LESLIE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_8ae617e7d7c877f89bc6583980a922d6.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_f571201f4a69351b048ca7dc30585b30_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#F58220", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_f571201f4a69351b048ca7dc30585b30_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_f571201f4a69351b048ca7dc30585b30 = L.geoJson(null, {
                onEachFeature: geo_json_f571201f4a69351b048ca7dc30585b30_onEachFeature,
            
                style: geo_json_f571201f4a69351b048ca7dc30585b30_styler,
            ...{
}
        });

        function geo_json_f571201f4a69351b048ca7dc30585b30_add (data) {
            geo_json_f571201f4a69351b048ca7dc30585b30
                .addData(data);
        }
            geo_json_f571201f4a69351b048ca7dc30585b30_add({"features": [{"geometry": {"coordinates": [[-79.396565, 43.900932], [-79.396041, 43.898855], [-79.395299, 43.895963], [-79.394872, 43.893986], [-79.393927, 43.890158], [-79.393391, 43.888245], [-79.392934, 43.886649], [-79.391734, 43.880636], [-79.39092, 43.877818], [-79.389898, 43.87368], [-79.388736, 43.869555], [-79.387789, 43.865758], [-79.387151, 43.862688], [-79.38573, 43.857149], [-79.384694, 43.852986], [-79.384155, 43.851036], [-79.383603, 43.848726], [-79.382563, 43.844713], [-79.381863, 43.842087], [-79.381062, 43.838835], [-79.379788, 43.833875], [-79.375664, 43.831165], [-79.372032, 43.829082], [-79.371314, 43.826734], [-79.369937, 43.82163], [-79.367274, 43.819227], [-79.362201, 43.814192], [-79.361138, 43.811731], [-79.35924, 43.809063], [-79.357016, 43.807101], [-79.354906, 43.805007], [-79.353481, 43.802539], [-79.354216, 43.799793], [-79.354822, 43.798001], [-79.355294, 43.796564], [-79.354963, 43.792903], [-79.354292, 43.790394], [-79.353216, 43.787472], [-79.353032, 43.78402], [-79.35234, 43.782346], [-79.345935, 43.779576], [-79.34506, 43.775683]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_f571201f4a69351b048ca7dc30585b30.bindTooltip(
                `<div>
                     90 LESLIE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_f571201f4a69351b048ca7dc30585b30.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_4c53dc374fd8ceec445c5e9dd1124c57_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#F58220", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_4c53dc374fd8ceec445c5e9dd1124c57_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_4c53dc374fd8ceec445c5e9dd1124c57 = L.geoJson(null, {
                onEachFeature: geo_json_4c53dc374fd8ceec445c5e9dd1124c57_onEachFeature,
            
                style: geo_json_4c53dc374fd8ceec445c5e9dd1124c57_styler,
            ...{
}
        });

        function geo_json_4c53dc374fd8ceec445c5e9dd1124c57_add (data) {
            geo_json_4c53dc374fd8ceec445c5e9dd1124c57
                .addData(data);
        }
            geo_json_4c53dc374fd8ceec445c5e9dd1124c57_add({"features": [{"geometry": {"coordinates": [[-79.360853, 43.81163], [-79.361859, 43.813989], [-79.366706, 43.8192], [-79.369799, 43.822068], [-79.370925, 43.826409], [-79.371997, 43.829491], [-79.377225, 43.831661], [-79.379357, 43.833513], [-79.380956, 43.840048], [-79.381461, 43.841807], [-79.381944, 43.844139], [-79.383111, 43.848278], [-79.384221, 43.852543], [-79.385268, 43.856769], [-79.386068, 43.85951], [-79.386633, 43.861909], [-79.387484, 43.865594], [-79.388258, 43.869131], [-79.389439, 43.873207], [-79.390454, 43.876767], [-79.391327, 43.88034], [-79.392321, 43.885693], [-79.393474, 43.889722], [-79.394446, 43.893655], [-79.394941, 43.895489], [-79.395602, 43.898378], [-79.393049, 43.901698], [-79.395767, 43.903735], [-79.396565, 43.900932]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_4c53dc374fd8ceec445c5e9dd1124c57.bindTooltip(
                `<div>
                     90 LESLIE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_4c53dc374fd8ceec445c5e9dd1124c57.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_9b5b2c86ccaca5c19bfb02980558e92f_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A37C53", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_9b5b2c86ccaca5c19bfb02980558e92f_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_9b5b2c86ccaca5c19bfb02980558e92f = L.geoJson(null, {
                onEachFeature: geo_json_9b5b2c86ccaca5c19bfb02980558e92f_onEachFeature,
            
                style: geo_json_9b5b2c86ccaca5c19bfb02980558e92f_styler,
            ...{
}
        });

        function geo_json_9b5b2c86ccaca5c19bfb02980558e92f_add (data) {
            geo_json_9b5b2c86ccaca5c19bfb02980558e92f
                .addData(data);
        }
            geo_json_9b5b2c86ccaca5c19bfb02980558e92f_add({"features": [{"geometry": {"coordinates": [[-79.415048, 43.782136], [-79.416698, 43.78496], [-79.417335, 43.787532], [-79.417977, 43.790138], [-79.418316, 43.79149], [-79.418994, 43.794272], [-79.419892, 43.797916], [-79.41715, 43.798613], [-79.414578, 43.79915], [-79.411529, 43.799827], [-79.409432, 43.800293], [-79.405841, 43.801086], [-79.401813, 43.801966], [-79.397139, 43.804329], [-79.397983, 43.806131], [-79.398953, 43.810143], [-79.399528, 43.81249], [-79.400469, 43.816378], [-79.401031, 43.818961], [-79.401617, 43.821607], [-79.403256, 43.827992], [-79.403674, 43.829811], [-79.404444, 43.832527], [-79.404949, 43.834622], [-79.406529, 43.840517], [-79.407004, 43.842388], [-79.407656, 43.844919], [-79.40843, 43.847824], [-79.409373, 43.851765], [-79.409951, 43.854023], [-79.410517, 43.856027], [-79.410794, 43.857606], [-79.411642, 43.86081], [-79.41203, 43.862578], [-79.413098, 43.866798], [-79.413516, 43.86868], [-79.414324, 43.872027], [-79.41524, 43.875816], [-79.415764, 43.878074], [-79.416166, 43.87967], [-79.416943, 43.882699], [-79.417503, 43.885009], [-79.420497, 43.88695], [-79.42345, 43.886311], [-79.426417, 43.885673], [-79.427523, 43.88748], [-79.427498, 43.889659], [-79.424251, 43.890934], [-79.420651, 43.890923], [-79.419037, 43.889982]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_9b5b2c86ccaca5c19bfb02980558e92f.bindTooltip(
                `<div>
                     91 BAYVIEW
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_9b5b2c86ccaca5c19bfb02980558e92f.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_e2b03d78416ce9a4b9863fa5eae8862c_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A37C53", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_e2b03d78416ce9a4b9863fa5eae8862c_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_e2b03d78416ce9a4b9863fa5eae8862c = L.geoJson(null, {
                onEachFeature: geo_json_e2b03d78416ce9a4b9863fa5eae8862c_onEachFeature,
            
                style: geo_json_e2b03d78416ce9a4b9863fa5eae8862c_styler,
            ...{
}
        });

        function geo_json_e2b03d78416ce9a4b9863fa5eae8862c_add (data) {
            geo_json_e2b03d78416ce9a4b9863fa5eae8862c
                .addData(data);
        }
            geo_json_e2b03d78416ce9a4b9863fa5eae8862c_add({"features": [{"geometry": {"coordinates": [[-79.419037, 43.889982], [-79.4184, 43.887486], [-79.417865, 43.885392], [-79.417259, 43.882953], [-79.416569, 43.880167], [-79.416026, 43.877896], [-79.415424, 43.875413], [-79.414715, 43.872415], [-79.413927, 43.869023], [-79.413427, 43.867023], [-79.412405, 43.862989], [-79.411969, 43.861189], [-79.411239, 43.858141], [-79.410691, 43.856002], [-79.410168, 43.853831], [-79.409795, 43.852127], [-79.408834, 43.848219], [-79.408127, 43.845365], [-79.407322, 43.84223], [-79.406651, 43.839751], [-79.405387, 43.834918], [-79.404746, 43.832438], [-79.404126, 43.830088], [-79.403553, 43.827828], [-79.402064, 43.821857], [-79.401553, 43.819937], [-79.401208, 43.81825], [-79.400684, 43.81622], [-79.399895, 43.81278], [-79.399214, 43.809846], [-79.39832, 43.806439], [-79.396684, 43.803491], [-79.3976, 43.803048], [-79.400758, 43.802356], [-79.406159, 43.801191], [-79.409216, 43.800515], [-79.411703, 43.799966], [-79.414376, 43.799391], [-79.417001, 43.798816], [-79.419718, 43.796088], [-79.419191, 43.793992], [-79.418625, 43.791289], [-79.418069, 43.789452], [-79.417496, 43.7872], [-79.415048, 43.782136]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_e2b03d78416ce9a4b9863fa5eae8862c.bindTooltip(
                `<div>
                     91 BAYVIEW
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_e2b03d78416ce9a4b9863fa5eae8862c.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_30c86bba6fbc8ef1a4082b4bdb693648_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A37C53", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_30c86bba6fbc8ef1a4082b4bdb693648_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_30c86bba6fbc8ef1a4082b4bdb693648 = L.geoJson(null, {
                onEachFeature: geo_json_30c86bba6fbc8ef1a4082b4bdb693648_onEachFeature,
            
                style: geo_json_30c86bba6fbc8ef1a4082b4bdb693648_styler,
            ...{
}
        });

        function geo_json_30c86bba6fbc8ef1a4082b4bdb693648_add (data) {
            geo_json_30c86bba6fbc8ef1a4082b4bdb693648
                .addData(data);
        }
            geo_json_30c86bba6fbc8ef1a4082b4bdb693648_add({"features": [{"geometry": {"coordinates": [[-79.420497, 43.88695], [-79.42345, 43.886311], [-79.426417, 43.885673], [-79.427523, 43.88748], [-79.427498, 43.889659], [-79.424251, 43.890934], [-79.420651, 43.890923], [-79.419037, 43.889982]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_30c86bba6fbc8ef1a4082b4bdb693648.bindTooltip(
                `<div>
                     91 BAYVIEW
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_30c86bba6fbc8ef1a4082b4bdb693648.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_6eb0d4e82bb99227165e365aa2fef357_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#496E6E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_6eb0d4e82bb99227165e365aa2fef357_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_6eb0d4e82bb99227165e365aa2fef357 = L.geoJson(null, {
                onEachFeature: geo_json_6eb0d4e82bb99227165e365aa2fef357_onEachFeature,
            
                style: geo_json_6eb0d4e82bb99227165e365aa2fef357_styler,
            ...{
}
        });

        function geo_json_6eb0d4e82bb99227165e365aa2fef357_add (data) {
            geo_json_6eb0d4e82bb99227165e365aa2fef357
                .addData(data);
        }
            geo_json_6eb0d4e82bb99227165e365aa2fef357_add({"features": [{"geometry": {"coordinates": [[-79.512496, 43.778872], [-79.507342, 43.778448], [-79.503784, 43.779254], [-79.49483, 43.783164], [-79.495866, 43.786778], [-79.496384, 43.788729], [-79.498282, 43.796425], [-79.499094, 43.799931], [-79.49991, 43.802942], [-79.500702, 43.806213], [-79.501263, 43.808497], [-79.502041, 43.811579], [-79.502801, 43.814605], [-79.503347, 43.816816], [-79.503705, 43.818309], [-79.5047, 43.822241], [-79.505361, 43.82489], [-79.505788, 43.826584], [-79.506316, 43.828896], [-79.506832, 43.831459], [-79.507181, 43.83329], [-79.50783, 43.836238], [-79.508534, 43.839134], [-79.509257, 43.842034], [-79.510168, 43.845448], [-79.511249, 43.850258], [-79.511825, 43.852815], [-79.512368, 43.855387], [-79.512681, 43.856528], [-79.513123, 43.858642], [-79.513636, 43.860795], [-79.514573, 43.864946], [-79.515086, 43.867317], [-79.515529, 43.869314], [-79.516421, 43.873204], [-79.517539, 43.87788], [-79.519614, 43.886653], [-79.520249, 43.889585], [-79.520696, 43.891656], [-79.522026, 43.897112], [-79.52293, 43.901432], [-79.52362, 43.904638], [-79.523063, 43.910504], [-79.525401, 43.918719], [-79.525996, 43.920819], [-79.52694, 43.924261], [-79.528048, 43.928413], [-79.527194, 43.928866], [-79.522153, 43.929983], [-79.518152, 43.930854], [-79.513034, 43.931931], [-79.510364, 43.932558], [-79.505375, 43.933752], [-79.481791, 43.938772], [-79.475214, 43.940128], [-79.468005, 43.941752], [-79.464255, 43.942508], [-79.458623, 43.943741], [-79.454715, 43.945095], [-79.455386, 43.948224], [-79.455859, 43.950171], [-79.456268, 43.951671], [-79.456841, 43.954832], [-79.457668, 43.958441], [-79.458595, 43.962687], [-79.459201, 43.965164], [-79.460094, 43.96891], [-79.461004, 43.972623], [-79.462081, 43.977299], [-79.462813, 43.980635], [-79.463698, 43.984317], [-79.464179, 43.986377], [-79.46446, 43.987502], [-79.465357, 43.990762], [-79.466121, 43.994063], [-79.466738, 43.996631], [-79.467575, 43.999943], [-79.468538, 44.004002], [-79.469037, 44.00628], [-79.469693, 44.008802], [-79.47081, 44.01389], [-79.472084, 44.019356], [-79.47364, 44.026442], [-79.475045, 44.032599], [-79.475434, 44.034363], [-79.475949, 44.03673], [-79.476668, 44.039916], [-79.4792, 44.045301], [-79.482157, 44.044815], [-79.484305, 44.046441], [-79.484627, 44.048227], [-79.484517, 44.049968], [-79.484547, 44.051922], [-79.486008, 44.052684]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_6eb0d4e82bb99227165e365aa2fef357.bindTooltip(
                `<div>
                     96 KEELE - YONGE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_6eb0d4e82bb99227165e365aa2fef357.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_62b6164968b18dc1e25e0623e615e17e_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#496E6E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_62b6164968b18dc1e25e0623e615e17e_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_62b6164968b18dc1e25e0623e615e17e = L.geoJson(null, {
                onEachFeature: geo_json_62b6164968b18dc1e25e0623e615e17e_onEachFeature,
            
                style: geo_json_62b6164968b18dc1e25e0623e615e17e_styler,
            ...{
}
        });

        function geo_json_62b6164968b18dc1e25e0623e615e17e_add (data) {
            geo_json_62b6164968b18dc1e25e0623e615e17e
                .addData(data);
        }
            geo_json_62b6164968b18dc1e25e0623e615e17e_add({"features": [{"geometry": {"coordinates": [[-79.486008, 44.052684], [-79.484808, 44.051979], [-79.48463, 44.050258], [-79.484776, 44.048387], [-79.484382, 44.046147], [-79.482819, 44.04479], [-79.47988, 44.044995], [-79.478417, 44.045301], [-79.477146, 44.040394], [-79.476136, 44.035685], [-79.475459, 44.033086], [-79.474094, 44.026787], [-79.472208, 44.01845], [-79.471047, 44.013564], [-79.469833, 44.00852], [-79.469345, 44.006481], [-79.468625, 44.003562], [-79.46778, 44.000178], [-79.46697, 43.996791], [-79.466302, 43.994172], [-79.465388, 43.99008], [-79.464662, 43.986869], [-79.463744, 43.983182], [-79.46255, 43.977941], [-79.461297, 43.972606], [-79.460309, 43.968505], [-79.459051, 43.963169], [-79.458209, 43.959468], [-79.457341, 43.955254], [-79.456443, 43.951598], [-79.456186, 43.950338], [-79.455809, 43.948727], [-79.45532, 43.946664], [-79.45489, 43.944757], [-79.455442, 43.944515], [-79.458255, 43.943957], [-79.463956, 43.942742], [-79.467601, 43.941975], [-79.47468, 43.940446], [-79.480836, 43.93916], [-79.504718, 43.934148], [-79.509736, 43.932861], [-79.513327, 43.932102], [-79.517686, 43.931094], [-79.521532, 43.930238], [-79.52588, 43.929291], [-79.526924, 43.923518], [-79.526062, 43.920211], [-79.52345, 43.910949], [-79.52393, 43.904687], [-79.52312, 43.90066], [-79.522352, 43.89734], [-79.521276, 43.892612], [-79.520532, 43.889606], [-79.520038, 43.887469], [-79.516835, 43.873589], [-79.515931, 43.86976], [-79.515487, 43.867808], [-79.514639, 43.8644], [-79.51395, 43.861251], [-79.51343, 43.859086], [-79.512939, 43.856885], [-79.512547, 43.855097], [-79.51201, 43.852815], [-79.511528, 43.850705], [-79.510419, 43.845755], [-79.50971, 43.84245], [-79.508947, 43.839456], [-79.508349, 43.836633], [-79.507547, 43.83357], [-79.507021, 43.831135], [-79.506713, 43.829386], [-79.506042, 43.826412], [-79.505668, 43.824947], [-79.505031, 43.822566], [-79.504144, 43.818744], [-79.503692, 43.816912], [-79.503226, 43.814987], [-79.502354, 43.811577], [-79.501591, 43.808481], [-79.501032, 43.806255], [-79.500223, 43.802951], [-79.499334, 43.799172], [-79.498515, 43.796116], [-79.496816, 43.789141], [-79.496306, 43.7873], [-79.494723, 43.781775], [-79.504245, 43.779419], [-79.510792, 43.777917], [-79.512496, 43.778872]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_62b6164968b18dc1e25e0623e615e17e.bindTooltip(
                `<div>
                     96 KEELE - YONGE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_62b6164968b18dc1e25e0623e615e17e.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_e4a715dde2a95ffe7c0d05e95d18da58_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#496E6E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_e4a715dde2a95ffe7c0d05e95d18da58_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_e4a715dde2a95ffe7c0d05e95d18da58 = L.geoJson(null, {
                onEachFeature: geo_json_e4a715dde2a95ffe7c0d05e95d18da58_onEachFeature,
            
                style: geo_json_e4a715dde2a95ffe7c0d05e95d18da58_styler,
            ...{
}
        });

        function geo_json_e4a715dde2a95ffe7c0d05e95d18da58_add (data) {
            geo_json_e4a715dde2a95ffe7c0d05e95d18da58
                .addData(data);
        }
            geo_json_e4a715dde2a95ffe7c0d05e95d18da58_add({"features": [{"geometry": {"coordinates": [[-79.512496, 43.778872], [-79.507342, 43.778448], [-79.503784, 43.779254], [-79.49483, 43.783164], [-79.495866, 43.786778], [-79.496384, 43.788729], [-79.498282, 43.796425], [-79.499094, 43.799931], [-79.49991, 43.802942], [-79.500702, 43.806213], [-79.501263, 43.808497], [-79.502041, 43.811579], [-79.502801, 43.814605], [-79.503347, 43.816816], [-79.503705, 43.818309], [-79.5047, 43.822241], [-79.505361, 43.82489], [-79.505788, 43.826584], [-79.506316, 43.828896], [-79.506832, 43.831459], [-79.507181, 43.83329], [-79.50783, 43.836238], [-79.508534, 43.839134], [-79.509257, 43.842034], [-79.510168, 43.845448], [-79.511249, 43.850258], [-79.511825, 43.852815], [-79.512368, 43.855387], [-79.512681, 43.856528], [-79.513123, 43.858642], [-79.513636, 43.860795], [-79.514573, 43.864946], [-79.515086, 43.867317], [-79.515529, 43.869314], [-79.516421, 43.873204], [-79.517539, 43.87788], [-79.519614, 43.886653], [-79.517301, 43.887683], [-79.518155, 43.889888], [-79.516432, 43.891482], [-79.513524, 43.891819], [-79.512602, 43.893657], [-79.520669, 43.891913], [-79.522026, 43.897112], [-79.52293, 43.901432], [-79.52362, 43.904638], [-79.523063, 43.910504], [-79.525401, 43.918719], [-79.525996, 43.920819], [-79.52694, 43.924261], [-79.528048, 43.928413], [-79.527194, 43.928866], [-79.522153, 43.929983], [-79.518152, 43.930854], [-79.513034, 43.931931], [-79.510364, 43.932558], [-79.505375, 43.933752], [-79.481791, 43.938772], [-79.475214, 43.940128], [-79.468005, 43.941752], [-79.464255, 43.942508], [-79.458623, 43.943741], [-79.454715, 43.945095], [-79.455386, 43.948224], [-79.455859, 43.950171], [-79.456268, 43.951671], [-79.456841, 43.954832], [-79.457668, 43.958441], [-79.458595, 43.962687], [-79.459201, 43.965164], [-79.460094, 43.96891], [-79.461004, 43.972623], [-79.462081, 43.977299], [-79.462813, 43.980635], [-79.463698, 43.984317], [-79.464179, 43.986377], [-79.46446, 43.987502], [-79.465357, 43.990762], [-79.466121, 43.994063], [-79.466738, 43.996631], [-79.467575, 43.999943], [-79.468538, 44.004002], [-79.469037, 44.00628], [-79.469693, 44.008802], [-79.47081, 44.01389], [-79.472084, 44.019356], [-79.47364, 44.026442], [-79.475045, 44.032599], [-79.475434, 44.034363], [-79.475949, 44.03673], [-79.476668, 44.039916], [-79.4792, 44.045301], [-79.482157, 44.044815], [-79.484305, 44.046441], [-79.484627, 44.048227], [-79.484517, 44.049968], [-79.484547, 44.051922], [-79.486008, 44.052684]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_e4a715dde2a95ffe7c0d05e95d18da58.bindTooltip(
                `<div>
                     96 KEELE - YONGE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_e4a715dde2a95ffe7c0d05e95d18da58.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_b00b77293e3112e052c6c048e1df03b3_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#496E6E", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_b00b77293e3112e052c6c048e1df03b3_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_b00b77293e3112e052c6c048e1df03b3 = L.geoJson(null, {
                onEachFeature: geo_json_b00b77293e3112e052c6c048e1df03b3_onEachFeature,
            
                style: geo_json_b00b77293e3112e052c6c048e1df03b3_styler,
            ...{
}
        });

        function geo_json_b00b77293e3112e052c6c048e1df03b3_add (data) {
            geo_json_b00b77293e3112e052c6c048e1df03b3
                .addData(data);
        }
            geo_json_b00b77293e3112e052c6c048e1df03b3_add({"features": [{"geometry": {"coordinates": [[-79.486008, 44.052684], [-79.484808, 44.051979], [-79.48463, 44.050258], [-79.484776, 44.048387], [-79.484382, 44.046147], [-79.482819, 44.04479], [-79.47988, 44.044995], [-79.478417, 44.045301], [-79.477146, 44.040394], [-79.476136, 44.035685], [-79.475459, 44.033086], [-79.474094, 44.026787], [-79.472208, 44.01845], [-79.471047, 44.013564], [-79.469833, 44.00852], [-79.469345, 44.006481], [-79.468625, 44.003562], [-79.46778, 44.000178], [-79.46697, 43.996791], [-79.466302, 43.994172], [-79.465388, 43.99008], [-79.464662, 43.986869], [-79.463744, 43.983182], [-79.46255, 43.977941], [-79.461297, 43.972606], [-79.460309, 43.968505], [-79.459051, 43.963169], [-79.458209, 43.959468], [-79.457341, 43.955254], [-79.456443, 43.951598], [-79.456186, 43.950338], [-79.455809, 43.948727], [-79.45532, 43.946664], [-79.45489, 43.944757], [-79.455442, 43.944515], [-79.458255, 43.943957], [-79.463956, 43.942742], [-79.467601, 43.941975], [-79.47468, 43.940446], [-79.480836, 43.93916], [-79.504718, 43.934148], [-79.509736, 43.932861], [-79.513327, 43.932102], [-79.517686, 43.931094], [-79.521532, 43.930238], [-79.52588, 43.929291], [-79.526924, 43.923518], [-79.526062, 43.920211], [-79.52345, 43.910949], [-79.52393, 43.904687], [-79.52312, 43.90066], [-79.522352, 43.89734], [-79.521276, 43.892612], [-79.512896, 43.893688], [-79.51395, 43.891804], [-79.516222, 43.891577], [-79.51833, 43.890323], [-79.517802, 43.888452], [-79.518877, 43.887018], [-79.516835, 43.873589], [-79.515931, 43.86976], [-79.515487, 43.867808], [-79.514639, 43.8644], [-79.51395, 43.861251], [-79.51343, 43.859086], [-79.512939, 43.856885], [-79.512547, 43.855097], [-79.51201, 43.852815], [-79.511528, 43.850705], [-79.510419, 43.845755], [-79.50971, 43.84245], [-79.508947, 43.839456], [-79.508349, 43.836633], [-79.507547, 43.83357], [-79.507021, 43.831135], [-79.506713, 43.829386], [-79.506042, 43.826412], [-79.505668, 43.824947], [-79.505031, 43.822566], [-79.504144, 43.818744], [-79.503692, 43.816912], [-79.503226, 43.814987], [-79.502354, 43.811577], [-79.501591, 43.808481], [-79.501032, 43.806255], [-79.500223, 43.802951], [-79.499334, 43.799172], [-79.498515, 43.796116], [-79.496816, 43.789141], [-79.496306, 43.7873], [-79.494723, 43.781775], [-79.504245, 43.779419], [-79.510792, 43.777917], [-79.512496, 43.778872]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_b00b77293e3112e052c6c048e1df03b3.bindTooltip(
                `<div>
                     96 KEELE - YONGE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_b00b77293e3112e052c6c048e1df03b3.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_f933dfc6e9433075d46d92d8632b04af_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#007647", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_f933dfc6e9433075d46d92d8632b04af_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_f933dfc6e9433075d46d92d8632b04af = L.geoJson(null, {
                onEachFeature: geo_json_f933dfc6e9433075d46d92d8632b04af_onEachFeature,
            
                style: geo_json_f933dfc6e9433075d46d92d8632b04af_styler,
            ...{
}
        });

        function geo_json_f933dfc6e9433075d46d92d8632b04af_add (data) {
            geo_json_f933dfc6e9433075d46d92d8632b04af
                .addData(data);
        }
            geo_json_f933dfc6e9433075d46d92d8632b04af_add({"features": [{"geometry": {"coordinates": [[-79.441606, 43.894734], [-79.443299, 43.89848], [-79.444081, 43.901573], [-79.444742, 43.904543], [-79.445549, 43.907563], [-79.446548, 43.911482], [-79.447089, 43.913846], [-79.447782, 43.916541], [-79.449146, 43.921873], [-79.450276, 43.925991], [-79.451267, 43.92901], [-79.45338, 43.939615], [-79.453832, 43.941634], [-79.454238, 43.943311], [-79.454715, 43.945095], [-79.455386, 43.948224], [-79.455859, 43.950171], [-79.456268, 43.951671], [-79.456841, 43.954832], [-79.457668, 43.958441], [-79.458595, 43.962687], [-79.459201, 43.965164], [-79.460094, 43.96891], [-79.461004, 43.972623], [-79.462081, 43.977299], [-79.462813, 43.980635], [-79.463698, 43.984317], [-79.464179, 43.986377], [-79.46446, 43.987502], [-79.465357, 43.990762], [-79.466121, 43.994063], [-79.466738, 43.996631], [-79.467575, 43.999943], [-79.468538, 44.004002], [-79.469037, 44.00628], [-79.469693, 44.008802], [-79.47081, 44.01389], [-79.472084, 44.019356], [-79.47364, 44.026442], [-79.475045, 44.032599], [-79.475434, 44.034363], [-79.475949, 44.03673], [-79.476668, 44.039916], [-79.4792, 44.045301], [-79.482157, 44.044815], [-79.484305, 44.046441], [-79.484627, 44.048227], [-79.484517, 44.049968], [-79.484547, 44.051922], [-79.486433, 44.052662], [-79.485781, 44.053567], [-79.48104, 44.05851], [-79.481709, 44.060872], [-79.48247, 44.064102], [-79.483384, 44.067795], [-79.487458, 44.071061], [-79.485451, 44.072654]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_f933dfc6e9433075d46d92d8632b04af.bindTooltip(
                `<div>
                     98 YONGE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_f933dfc6e9433075d46d92d8632b04af.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_4299659d9f1600b4399f8a7bca6a4eb6_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#007647", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_4299659d9f1600b4399f8a7bca6a4eb6_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_4299659d9f1600b4399f8a7bca6a4eb6 = L.geoJson(null, {
                onEachFeature: geo_json_4299659d9f1600b4399f8a7bca6a4eb6_onEachFeature,
            
                style: geo_json_4299659d9f1600b4399f8a7bca6a4eb6_styler,
            ...{
}
        });

        function geo_json_4299659d9f1600b4399f8a7bca6a4eb6_add (data) {
            geo_json_4299659d9f1600b4399f8a7bca6a4eb6
                .addData(data);
        }
            geo_json_4299659d9f1600b4399f8a7bca6a4eb6_add({"features": [{"geometry": {"coordinates": [[-79.485451, 44.072654], [-79.484559, 44.071102], [-79.483827, 44.068092], [-79.483455, 44.066601], [-79.482941, 44.064597], [-79.482177, 44.061349], [-79.480711, 44.055096], [-79.483716, 44.054279], [-79.486433, 44.052662], [-79.485781, 44.053567], [-79.483007, 44.054155], [-79.48074, 44.054598], [-79.480129, 44.053025], [-79.479677, 44.051177], [-79.479298, 44.049546], [-79.478882, 44.047833], [-79.478478, 44.045766], [-79.477146, 44.040394], [-79.476136, 44.035685], [-79.475459, 44.033086], [-79.474094, 44.026787], [-79.472208, 44.01845], [-79.471047, 44.013564], [-79.469833, 44.00852], [-79.469345, 44.006481], [-79.468625, 44.003562], [-79.46778, 44.000178], [-79.46697, 43.996791], [-79.466302, 43.994172], [-79.465388, 43.99008], [-79.464662, 43.986869], [-79.463744, 43.983182], [-79.46255, 43.977941], [-79.461297, 43.972606], [-79.460309, 43.968505], [-79.459051, 43.963169], [-79.458209, 43.959468], [-79.457341, 43.955254], [-79.456443, 43.951598], [-79.456186, 43.950338], [-79.455809, 43.948727], [-79.45532, 43.946664], [-79.45489, 43.944757], [-79.454291, 43.942266], [-79.453825, 43.940082], [-79.451745, 43.929207], [-79.450616, 43.926214], [-79.449919, 43.923781], [-79.448117, 43.916596], [-79.447534, 43.914257], [-79.446945, 43.911874], [-79.446084, 43.908107], [-79.445298, 43.90495], [-79.444488, 43.901299], [-79.443908, 43.898838], [-79.441606, 43.894734]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_4299659d9f1600b4399f8a7bca6a4eb6.bindTooltip(
                `<div>
                     98 YONGE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_4299659d9f1600b4399f8a7bca6a4eb6.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_e86d8d992f2c35b80a8dcc82931779eb_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#684287", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_e86d8d992f2c35b80a8dcc82931779eb_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_e86d8d992f2c35b80a8dcc82931779eb = L.geoJson(null, {
                onEachFeature: geo_json_e86d8d992f2c35b80a8dcc82931779eb_onEachFeature,
            
                style: geo_json_e86d8d992f2c35b80a8dcc82931779eb_styler,
            ...{
}
        });

        function geo_json_e86d8d992f2c35b80a8dcc82931779eb_add (data) {
            geo_json_e86d8d992f2c35b80a8dcc82931779eb
                .addData(data);
        }
            geo_json_e86d8d992f2c35b80a8dcc82931779eb_add({"features": [{"geometry": {"coordinates": [[-79.414795, 43.782426], [-79.416698, 43.78496], [-79.417335, 43.787532], [-79.417977, 43.790138], [-79.418316, 43.79149], [-79.418994, 43.794272], [-79.42011, 43.798695], [-79.420878, 43.801684], [-79.421756, 43.805238], [-79.422192, 43.807001], [-79.423127, 43.810912], [-79.42381, 43.814029], [-79.424299, 43.816215], [-79.425788, 43.822633], [-79.426318, 43.824924], [-79.426813, 43.827024], [-79.427303, 43.828884], [-79.427555, 43.830103], [-79.428022, 43.832324], [-79.429307, 43.838465], [-79.425301, 43.83968], [-79.429968, 43.841201], [-79.430649, 43.844229], [-79.431258, 43.846668], [-79.43183, 43.848956], [-79.432374, 43.851295], [-79.432974, 43.853602], [-79.43334, 43.855265], [-79.434036, 43.858256], [-79.434437, 43.860022], [-79.434891, 43.861968], [-79.435279, 43.863709], [-79.435931, 43.866482], [-79.436556, 43.869222], [-79.43693, 43.870716], [-79.437717, 43.874235], [-79.438224, 43.876169], [-79.438754, 43.878261], [-79.439272, 43.88046], [-79.439731, 43.882565], [-79.440261, 43.884941], [-79.440604, 43.886598], [-79.441423, 43.890207], [-79.441377, 43.894757]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_e86d8d992f2c35b80a8dcc82931779eb.bindTooltip(
                `<div>
                     99 YONGE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_e86d8d992f2c35b80a8dcc82931779eb.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_e5bd49d06f02d394ad21d42b90b4903a_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#684287", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_e5bd49d06f02d394ad21d42b90b4903a_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_e5bd49d06f02d394ad21d42b90b4903a = L.geoJson(null, {
                onEachFeature: geo_json_e5bd49d06f02d394ad21d42b90b4903a_onEachFeature,
            
                style: geo_json_e5bd49d06f02d394ad21d42b90b4903a_styler,
            ...{
}
        });

        function geo_json_e5bd49d06f02d394ad21d42b90b4903a_add (data) {
            geo_json_e5bd49d06f02d394ad21d42b90b4903a
                .addData(data);
        }
            geo_json_e5bd49d06f02d394ad21d42b90b4903a_add({"features": [{"geometry": {"coordinates": [[-79.425301, 43.83968], [-79.429968, 43.841201], [-79.430649, 43.844229], [-79.431258, 43.846668], [-79.43183, 43.848956], [-79.432374, 43.851295], [-79.432974, 43.853602], [-79.43334, 43.855265], [-79.434036, 43.858256], [-79.434437, 43.860022], [-79.434891, 43.861968], [-79.435279, 43.863709], [-79.435931, 43.866482], [-79.436556, 43.869222], [-79.43693, 43.870716], [-79.437717, 43.874235], [-79.438224, 43.876169], [-79.438754, 43.878261], [-79.439272, 43.88046], [-79.439731, 43.882565], [-79.440261, 43.884941], [-79.440604, 43.886598], [-79.441423, 43.890207], [-79.441377, 43.894757]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_e5bd49d06f02d394ad21d42b90b4903a.bindTooltip(
                `<div>
                     99 YONGE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_e5bd49d06f02d394ad21d42b90b4903a.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_31e3f82e02ed8ac4b2b1df0a5d499a6e_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#684287", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_31e3f82e02ed8ac4b2b1df0a5d499a6e_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_31e3f82e02ed8ac4b2b1df0a5d499a6e = L.geoJson(null, {
                onEachFeature: geo_json_31e3f82e02ed8ac4b2b1df0a5d499a6e_onEachFeature,
            
                style: geo_json_31e3f82e02ed8ac4b2b1df0a5d499a6e_styler,
            ...{
}
        });

        function geo_json_31e3f82e02ed8ac4b2b1df0a5d499a6e_add (data) {
            geo_json_31e3f82e02ed8ac4b2b1df0a5d499a6e
                .addData(data);
        }
            geo_json_31e3f82e02ed8ac4b2b1df0a5d499a6e_add({"features": [{"geometry": {"coordinates": [[-79.441377, 43.894757], [-79.441599, 43.889039], [-79.441063, 43.886954], [-79.440636, 43.885006], [-79.440034, 43.882786], [-79.439322, 43.8795], [-79.43898, 43.878121], [-79.438322, 43.875626], [-79.437899, 43.873782], [-79.437395, 43.871435], [-79.437086, 43.869505], [-79.436474, 43.86678], [-79.435828, 43.864177], [-79.435526, 43.862826], [-79.435013, 43.860639], [-79.434583, 43.858768], [-79.433883, 43.855794], [-79.433308, 43.853302], [-79.432818, 43.851521], [-79.432549, 43.850147], [-79.432098, 43.848431], [-79.431706, 43.846539], [-79.431204, 43.84459], [-79.430455, 43.841704], [-79.42523, 43.839711], [-79.429701, 43.83824], [-79.429351, 43.836591], [-79.428506, 43.832738], [-79.42804, 43.83072], [-79.427575, 43.828851], [-79.427091, 43.826823], [-79.42672, 43.825278], [-79.426035, 43.822276], [-79.424704, 43.816482], [-79.424259, 43.814736], [-79.423491, 43.811126], [-79.422566, 43.807246], [-79.422211, 43.805597], [-79.4213, 43.802036], [-79.420274, 43.798244], [-79.420037, 43.797434], [-79.419718, 43.796088], [-79.419191, 43.793992], [-79.418625, 43.791289], [-79.418069, 43.789452], [-79.417496, 43.7872], [-79.414795, 43.782426]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_31e3f82e02ed8ac4b2b1df0a5d499a6e.bindTooltip(
                `<div>
                     99 YONGE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_31e3f82e02ed8ac4b2b1df0a5d499a6e.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_0e3169d4d2b1127144a83adeccad48ef_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#6DC069", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_0e3169d4d2b1127144a83adeccad48ef_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_0e3169d4d2b1127144a83adeccad48ef = L.geoJson(null, {
                onEachFeature: geo_json_0e3169d4d2b1127144a83adeccad48ef_onEachFeature,
            
                style: geo_json_0e3169d4d2b1127144a83adeccad48ef_styler,
            ...{
}
        });

        function geo_json_0e3169d4d2b1127144a83adeccad48ef_add (data) {
            geo_json_0e3169d4d2b1127144a83adeccad48ef
                .addData(data);
        }
            geo_json_0e3169d4d2b1127144a83adeccad48ef_add({"features": [{"geometry": {"coordinates": [[-79.462293, 43.749718], [-79.462635, 43.750558], [-79.464767, 43.757578], [-79.464971, 43.76088], [-79.465469, 43.763081], [-79.46601, 43.76538], [-79.466659, 43.768599], [-79.46689, 43.769632], [-79.468308, 43.775094], [-79.468675, 43.776586], [-79.468983, 43.777843], [-79.469688, 43.780758], [-79.470034, 43.783718], [-79.469912, 43.787084], [-79.470008, 43.787737], [-79.470264, 43.788675], [-79.471135, 43.792145], [-79.471432, 43.793155], [-79.471675, 43.794345], [-79.472253, 43.79695], [-79.472711, 43.798891], [-79.473351, 43.801344], [-79.474335, 43.805466], [-79.475228, 43.809511], [-79.475871, 43.813011], [-79.476295, 43.814985], [-79.478308, 43.823754], [-79.480908, 43.829489]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_0e3169d4d2b1127144a83adeccad48ef.bindTooltip(
                `<div>
                     105 DUFFERIN
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_0e3169d4d2b1127144a83adeccad48ef.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_588dd4cc9940c093cd9c2e2acbcbc382_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#6DC069", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_588dd4cc9940c093cd9c2e2acbcbc382_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_588dd4cc9940c093cd9c2e2acbcbc382 = L.geoJson(null, {
                onEachFeature: geo_json_588dd4cc9940c093cd9c2e2acbcbc382_onEachFeature,
            
                style: geo_json_588dd4cc9940c093cd9c2e2acbcbc382_styler,
            ...{
}
        });

        function geo_json_588dd4cc9940c093cd9c2e2acbcbc382_add (data) {
            geo_json_588dd4cc9940c093cd9c2e2acbcbc382
                .addData(data);
        }
            geo_json_588dd4cc9940c093cd9c2e2acbcbc382_add({"features": [{"geometry": {"coordinates": [[-79.480908, 43.829489], [-79.486046, 43.828824], [-79.489816, 43.830485], [-79.492749, 43.834415], [-79.492457, 43.835793], [-79.491583, 43.83729], [-79.491953, 43.840146], [-79.487236, 43.841654], [-79.483409, 43.842449], [-79.482598, 43.839922], [-79.481717, 43.836171], [-79.480317, 43.829855], [-79.478814, 43.824408], [-79.476696, 43.815394], [-79.476291, 43.813395], [-79.475623, 43.809803], [-79.474798, 43.805871], [-79.473661, 43.801302], [-79.47302, 43.798762], [-79.472559, 43.796826], [-79.472119, 43.794963], [-79.47142, 43.791958], [-79.470774, 43.789369], [-79.470329, 43.787488], [-79.470257, 43.786727], [-79.470291, 43.784058], [-79.46997, 43.78096], [-79.469262, 43.778061], [-79.468586, 43.775275], [-79.467846, 43.77218], [-79.467189, 43.76919], [-79.466968, 43.768239], [-79.466348, 43.765571], [-79.465573, 43.76184], [-79.465148, 43.757967], [-79.46159, 43.748682]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_588dd4cc9940c093cd9c2e2acbcbc382.bindTooltip(
                `<div>
                     105 DUFFERIN
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_588dd4cc9940c093cd9c2e2acbcbc382.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_c1f659e81c36d963c1c6dc544621f940_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#6DC069", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_c1f659e81c36d963c1c6dc544621f940_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_c1f659e81c36d963c1c6dc544621f940 = L.geoJson(null, {
                onEachFeature: geo_json_c1f659e81c36d963c1c6dc544621f940_onEachFeature,
            
                style: geo_json_c1f659e81c36d963c1c6dc544621f940_styler,
            ...{
}
        });

        function geo_json_c1f659e81c36d963c1c6dc544621f940_add (data) {
            geo_json_c1f659e81c36d963c1c6dc544621f940
                .addData(data);
        }
            geo_json_c1f659e81c36d963c1c6dc544621f940_add({"features": [{"geometry": {"coordinates": [[-79.480908, 43.829489], [-79.486046, 43.828824], [-79.489816, 43.830485], [-79.492749, 43.834415], [-79.492457, 43.835793], [-79.491583, 43.83729], [-79.491953, 43.840146], [-79.487236, 43.841654], [-79.483409, 43.842449], [-79.482598, 43.839922], [-79.481717, 43.836171], [-79.480317, 43.829855]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_c1f659e81c36d963c1c6dc544621f940.bindTooltip(
                `<div>
                     105 DUFFERIN
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_c1f659e81c36d963c1c6dc544621f940.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_fd8d197b862447a18b3b6624f8df7e6c_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#6DC069", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_fd8d197b862447a18b3b6624f8df7e6c_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_fd8d197b862447a18b3b6624f8df7e6c = L.geoJson(null, {
                onEachFeature: geo_json_fd8d197b862447a18b3b6624f8df7e6c_onEachFeature,
            
                style: geo_json_fd8d197b862447a18b3b6624f8df7e6c_styler,
            ...{
}
        });

        function geo_json_fd8d197b862447a18b3b6624f8df7e6c_add (data) {
            geo_json_fd8d197b862447a18b3b6624f8df7e6c
                .addData(data);
        }
            geo_json_fd8d197b862447a18b3b6624f8df7e6c_add({"features": [{"geometry": {"coordinates": [[-79.462293, 43.749718], [-79.462635, 43.750558], [-79.464767, 43.757578], [-79.464971, 43.76088], [-79.465469, 43.763081], [-79.46601, 43.76538], [-79.466659, 43.768599], [-79.46689, 43.769632], [-79.468308, 43.775094], [-79.468675, 43.776586], [-79.468983, 43.777843], [-79.469688, 43.780758], [-79.470034, 43.783718], [-79.469912, 43.787084], [-79.470008, 43.787737], [-79.470264, 43.788675], [-79.471135, 43.792145], [-79.471432, 43.793155], [-79.471675, 43.794345], [-79.472253, 43.79695], [-79.472711, 43.798891], [-79.473351, 43.801344], [-79.474335, 43.805466], [-79.475228, 43.809511], [-79.475871, 43.813011], [-79.476295, 43.814985], [-79.478308, 43.823754], [-79.480908, 43.829489], [-79.486046, 43.828824], [-79.489816, 43.830485], [-79.492749, 43.834415], [-79.492457, 43.835793], [-79.491583, 43.83729], [-79.491953, 43.840146], [-79.491987, 43.8446], [-79.493158, 43.848341], [-79.494044, 43.850389], [-79.495591, 43.853554], [-79.497244, 43.855245], [-79.49792, 43.856589], [-79.498599, 43.858314], [-79.494105, 43.859507], [-79.487967, 43.861009], [-79.487076, 43.85879]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_fd8d197b862447a18b3b6624f8df7e6c.bindTooltip(
                `<div>
                     105 DUFFERIN
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_fd8d197b862447a18b3b6624f8df7e6c.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_2229b23b6f4ed7629cdc9d5888db2ab7_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#6DC069", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_2229b23b6f4ed7629cdc9d5888db2ab7_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_2229b23b6f4ed7629cdc9d5888db2ab7 = L.geoJson(null, {
                onEachFeature: geo_json_2229b23b6f4ed7629cdc9d5888db2ab7_onEachFeature,
            
                style: geo_json_2229b23b6f4ed7629cdc9d5888db2ab7_styler,
            ...{
}
        });

        function geo_json_2229b23b6f4ed7629cdc9d5888db2ab7_add (data) {
            geo_json_2229b23b6f4ed7629cdc9d5888db2ab7
                .addData(data);
        }
            geo_json_2229b23b6f4ed7629cdc9d5888db2ab7_add({"features": [{"geometry": {"coordinates": [[-79.480908, 43.829489], [-79.486046, 43.828824], [-79.489816, 43.830485], [-79.492749, 43.834415], [-79.492457, 43.835793], [-79.491583, 43.83729], [-79.491953, 43.840146], [-79.491987, 43.8446], [-79.493158, 43.848341], [-79.494044, 43.850389], [-79.495591, 43.853554], [-79.497244, 43.855245], [-79.49792, 43.856589], [-79.498599, 43.858314], [-79.494105, 43.859507], [-79.487967, 43.861009], [-79.487076, 43.85879]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_2229b23b6f4ed7629cdc9d5888db2ab7.bindTooltip(
                `<div>
                     105 DUFFERIN
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_2229b23b6f4ed7629cdc9d5888db2ab7.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_e28da6e0212a7fa84fff3901756b7840_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#6DC069", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_e28da6e0212a7fa84fff3901756b7840_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_e28da6e0212a7fa84fff3901756b7840 = L.geoJson(null, {
                onEachFeature: geo_json_e28da6e0212a7fa84fff3901756b7840_onEachFeature,
            
                style: geo_json_e28da6e0212a7fa84fff3901756b7840_styler,
            ...{
}
        });

        function geo_json_e28da6e0212a7fa84fff3901756b7840_add (data) {
            geo_json_e28da6e0212a7fa84fff3901756b7840
                .addData(data);
        }
            geo_json_e28da6e0212a7fa84fff3901756b7840_add({"features": [{"geometry": {"coordinates": [[-79.472253, 43.79695], [-79.472711, 43.798891], [-79.473351, 43.801344], [-79.474335, 43.805466], [-79.475228, 43.809511], [-79.475871, 43.813011], [-79.476295, 43.814985], [-79.478308, 43.823754], [-79.480908, 43.829489], [-79.486046, 43.828824], [-79.489816, 43.830485], [-79.492749, 43.834415], [-79.492457, 43.835793], [-79.491583, 43.83729], [-79.491953, 43.840146], [-79.491987, 43.8446], [-79.493158, 43.848341], [-79.494044, 43.850389], [-79.495591, 43.853554], [-79.497244, 43.855245], [-79.49792, 43.856589], [-79.498599, 43.858314], [-79.494105, 43.859507], [-79.487967, 43.861009], [-79.487076, 43.85879]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_e28da6e0212a7fa84fff3901756b7840.bindTooltip(
                `<div>
                     105 DUFFERIN
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_e28da6e0212a7fa84fff3901756b7840.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_85822b3030d857d6c01d53e2ab3b6c4b_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#6DC069", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_85822b3030d857d6c01d53e2ab3b6c4b_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_85822b3030d857d6c01d53e2ab3b6c4b = L.geoJson(null, {
                onEachFeature: geo_json_85822b3030d857d6c01d53e2ab3b6c4b_onEachFeature,
            
                style: geo_json_85822b3030d857d6c01d53e2ab3b6c4b_styler,
            ...{
}
        });

        function geo_json_85822b3030d857d6c01d53e2ab3b6c4b_add (data) {
            geo_json_85822b3030d857d6c01d53e2ab3b6c4b
                .addData(data);
        }
            geo_json_85822b3030d857d6c01d53e2ab3b6c4b_add({"features": [{"geometry": {"coordinates": [[-79.487076, 43.85879], [-79.48606, 43.854697], [-79.48508, 43.850591], [-79.484093, 43.846454], [-79.483277, 43.842854], [-79.482598, 43.839922], [-79.481717, 43.836171], [-79.480317, 43.829855], [-79.478814, 43.824408], [-79.476696, 43.815394], [-79.476291, 43.813395], [-79.475623, 43.809803], [-79.474798, 43.805871], [-79.473661, 43.801302], [-79.47302, 43.798762], [-79.472559, 43.796826], [-79.472119, 43.794963], [-79.47142, 43.791958], [-79.470774, 43.789369], [-79.470329, 43.787488], [-79.470257, 43.786727], [-79.470291, 43.784058], [-79.46997, 43.78096], [-79.469262, 43.778061], [-79.468586, 43.775275], [-79.467846, 43.77218], [-79.467189, 43.76919], [-79.466968, 43.768239], [-79.466348, 43.765571], [-79.465573, 43.76184], [-79.465148, 43.757967], [-79.46159, 43.748682]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_85822b3030d857d6c01d53e2ab3b6c4b.bindTooltip(
                `<div>
                     105 DUFFERIN
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_85822b3030d857d6c01d53e2ab3b6c4b.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_33f60927927563a21d305b55b46a9bb0_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00B547", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_33f60927927563a21d305b55b46a9bb0_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_33f60927927563a21d305b55b46a9bb0 = L.geoJson(null, {
                onEachFeature: geo_json_33f60927927563a21d305b55b46a9bb0_onEachFeature,
            
                style: geo_json_33f60927927563a21d305b55b46a9bb0_styler,
            ...{
}
        });

        function geo_json_33f60927927563a21d305b55b46a9bb0_add (data) {
            geo_json_33f60927927563a21d305b55b46a9bb0
                .addData(data);
        }
            geo_json_33f60927927563a21d305b55b46a9bb0_add({"features": [{"geometry": {"coordinates": [[-79.512542, 43.77902], [-79.507342, 43.778448], [-79.503784, 43.779254], [-79.49483, 43.783164], [-79.495866, 43.786778], [-79.496384, 43.788729], [-79.498282, 43.796425], [-79.499094, 43.799931], [-79.49991, 43.802942], [-79.500702, 43.806213], [-79.501263, 43.808497], [-79.502041, 43.811579], [-79.502801, 43.814605], [-79.503347, 43.816816], [-79.503705, 43.818309], [-79.5047, 43.822241], [-79.505361, 43.82489], [-79.505788, 43.826584], [-79.506316, 43.828896], [-79.506832, 43.831459], [-79.507181, 43.83329], [-79.50783, 43.836238], [-79.508534, 43.839134], [-79.509257, 43.842034], [-79.510168, 43.845448], [-79.511249, 43.850258], [-79.511825, 43.852815], [-79.512368, 43.855387], [-79.512681, 43.856528], [-79.513123, 43.858642], [-79.513636, 43.860795], [-79.514573, 43.864946], [-79.516166, 43.867529], [-79.519899, 43.866917], [-79.524698, 43.86596], [-79.528726, 43.865484], [-79.529847, 43.866972], [-79.529811, 43.8681], [-79.529572, 43.87026]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_33f60927927563a21d305b55b46a9bb0.bindTooltip(
                `<div>
                     107 KEELE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_33f60927927563a21d305b55b46a9bb0.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_947049ff5e26361d798ab8ee6980f683_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00B547", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_947049ff5e26361d798ab8ee6980f683_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_947049ff5e26361d798ab8ee6980f683 = L.geoJson(null, {
                onEachFeature: geo_json_947049ff5e26361d798ab8ee6980f683_onEachFeature,
            
                style: geo_json_947049ff5e26361d798ab8ee6980f683_styler,
            ...{
}
        });

        function geo_json_947049ff5e26361d798ab8ee6980f683_add (data) {
            geo_json_947049ff5e26361d798ab8ee6980f683
                .addData(data);
        }
            geo_json_947049ff5e26361d798ab8ee6980f683_add({"features": [{"geometry": {"coordinates": [[-79.50783, 43.836238], [-79.508534, 43.839134], [-79.509257, 43.842034], [-79.510168, 43.845448], [-79.511249, 43.850258], [-79.511825, 43.852815], [-79.512368, 43.855387], [-79.512681, 43.856528], [-79.513123, 43.858642], [-79.513636, 43.860795], [-79.514573, 43.864946], [-79.516166, 43.867529], [-79.519899, 43.866917], [-79.524698, 43.86596], [-79.528726, 43.865484], [-79.529847, 43.866972], [-79.529811, 43.8681], [-79.529572, 43.87026]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_947049ff5e26361d798ab8ee6980f683.bindTooltip(
                `<div>
                     107 KEELE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_947049ff5e26361d798ab8ee6980f683.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_23902044f24fbd41992c6555233fdf32_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00B547", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_23902044f24fbd41992c6555233fdf32_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_23902044f24fbd41992c6555233fdf32 = L.geoJson(null, {
                onEachFeature: geo_json_23902044f24fbd41992c6555233fdf32_onEachFeature,
            
                style: geo_json_23902044f24fbd41992c6555233fdf32_styler,
            ...{
}
        });

        function geo_json_23902044f24fbd41992c6555233fdf32_add (data) {
            geo_json_23902044f24fbd41992c6555233fdf32
                .addData(data);
        }
            geo_json_23902044f24fbd41992c6555233fdf32_add({"features": [{"geometry": {"coordinates": [[-79.529572, 43.87026], [-79.52454, 43.871608], [-79.516965, 43.87322], [-79.515931, 43.86976], [-79.515487, 43.867808], [-79.514639, 43.8644], [-79.51395, 43.861251], [-79.51343, 43.859086], [-79.512939, 43.856885], [-79.512547, 43.855097], [-79.51201, 43.852815], [-79.511528, 43.850705], [-79.510419, 43.845755], [-79.50971, 43.84245], [-79.508947, 43.839456], [-79.508349, 43.836633], [-79.507547, 43.83357], [-79.507021, 43.831135], [-79.506713, 43.829386], [-79.506042, 43.826412], [-79.505668, 43.824947], [-79.505031, 43.822566], [-79.504144, 43.818744], [-79.503692, 43.816912], [-79.503226, 43.814987], [-79.502354, 43.811577], [-79.501591, 43.808481], [-79.501032, 43.806255], [-79.500223, 43.802951], [-79.499334, 43.799172], [-79.498515, 43.796116], [-79.496816, 43.789141], [-79.496306, 43.7873], [-79.494723, 43.781775], [-79.504245, 43.779419], [-79.510792, 43.777917], [-79.512542, 43.77902]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_23902044f24fbd41992c6555233fdf32.bindTooltip(
                `<div>
                     107 KEELE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_23902044f24fbd41992c6555233fdf32.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_1a4dbbaa611f937fea7ec5eff29d444a_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00B547", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_1a4dbbaa611f937fea7ec5eff29d444a_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_1a4dbbaa611f937fea7ec5eff29d444a = L.geoJson(null, {
                onEachFeature: geo_json_1a4dbbaa611f937fea7ec5eff29d444a_onEachFeature,
            
                style: geo_json_1a4dbbaa611f937fea7ec5eff29d444a_styler,
            ...{
}
        });

        function geo_json_1a4dbbaa611f937fea7ec5eff29d444a_add (data) {
            geo_json_1a4dbbaa611f937fea7ec5eff29d444a
                .addData(data);
        }
            geo_json_1a4dbbaa611f937fea7ec5eff29d444a_add({"features": [{"geometry": {"coordinates": [[-79.529572, 43.87026], [-79.52454, 43.871608], [-79.516965, 43.87322], [-79.515931, 43.86976], [-79.515487, 43.867808]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_1a4dbbaa611f937fea7ec5eff29d444a.bindTooltip(
                `<div>
                     107 KEELE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_1a4dbbaa611f937fea7ec5eff29d444a.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_93be210a17e2915808314fb68967747f_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#C4A006", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_93be210a17e2915808314fb68967747f_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_93be210a17e2915808314fb68967747f = L.geoJson(null, {
                onEachFeature: geo_json_93be210a17e2915808314fb68967747f_onEachFeature,
            
                style: geo_json_93be210a17e2915808314fb68967747f_styler,
            ...{
}
        });

        function geo_json_93be210a17e2915808314fb68967747f_add (data) {
            geo_json_93be210a17e2915808314fb68967747f
                .addData(data);
        }
            geo_json_93be210a17e2915808314fb68967747f_add({"features": [{"geometry": {"coordinates": [[-79.511798, 43.77868], [-79.516748, 43.776552], [-79.522088, 43.775467], [-79.526648, 43.774423], [-79.531612, 43.773467], [-79.538326, 43.772108], [-79.540444, 43.771676], [-79.543089, 43.771103], [-79.543453, 43.771813], [-79.544607, 43.77726], [-79.545831, 43.782943], [-79.546576, 43.785987], [-79.547219, 43.789052], [-79.547397, 43.790033], [-79.548172, 43.792852], [-79.548919, 43.795976], [-79.549406, 43.798352], [-79.550489, 43.802882], [-79.551644, 43.807667], [-79.552476, 43.811144], [-79.553416, 43.814988], [-79.554772, 43.820737], [-79.555929, 43.825752], [-79.556448, 43.82777], [-79.55702, 43.830162], [-79.558073, 43.834204], [-79.558757, 43.837369], [-79.559406, 43.84038], [-79.559976, 43.842602], [-79.560405, 43.844678], [-79.55736, 43.845084], [-79.554366, 43.845382], [-79.540687, 43.847893]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_93be210a17e2915808314fb68967747f.bindTooltip(
                `<div>
                     165 WESTON
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_93be210a17e2915808314fb68967747f.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_f20b54b58817dcd985e66d70e5aabed8_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#C4A006", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_f20b54b58817dcd985e66d70e5aabed8_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_f20b54b58817dcd985e66d70e5aabed8 = L.geoJson(null, {
                onEachFeature: geo_json_f20b54b58817dcd985e66d70e5aabed8_onEachFeature,
            
                style: geo_json_f20b54b58817dcd985e66d70e5aabed8_styler,
            ...{
}
        });

        function geo_json_f20b54b58817dcd985e66d70e5aabed8_add (data) {
            geo_json_f20b54b58817dcd985e66d70e5aabed8
                .addData(data);
        }
            geo_json_f20b54b58817dcd985e66d70e5aabed8_add({"features": [{"geometry": {"coordinates": [[-79.540687, 43.847893], [-79.553825, 43.845763], [-79.556489, 43.84532], [-79.56058, 43.844173], [-79.560188, 43.84253], [-79.559867, 43.84096], [-79.559141, 43.837862], [-79.558483, 43.834708], [-79.558264, 43.833762], [-79.557495, 43.830644], [-79.556892, 43.828175], [-79.556516, 43.82662], [-79.555197, 43.821106], [-79.553834, 43.81542], [-79.552918, 43.811587], [-79.55211, 43.80819], [-79.550924, 43.803301], [-79.54984, 43.798667], [-79.549115, 43.795768], [-79.548584, 43.793204], [-79.547553, 43.788651], [-79.546997, 43.786366], [-79.546216, 43.783281], [-79.545069, 43.777854], [-79.543625, 43.771686], [-79.540804, 43.771401], [-79.538092, 43.771964], [-79.531985, 43.773194], [-79.527054, 43.774211], [-79.52212, 43.775206], [-79.520924, 43.775533], [-79.516435, 43.77638], [-79.511798, 43.77868]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_f20b54b58817dcd985e66d70e5aabed8.bindTooltip(
                `<div>
                     165 WESTON
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_f20b54b58817dcd985e66d70e5aabed8.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_2dfd0b3eb8d93a406e20399fe13c037e_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#8B0030", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_2dfd0b3eb8d93a406e20399fe13c037e_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_2dfd0b3eb8d93a406e20399fe13c037e = L.geoJson(null, {
                onEachFeature: geo_json_2dfd0b3eb8d93a406e20399fe13c037e_onEachFeature,
            
                style: geo_json_2dfd0b3eb8d93a406e20399fe13c037e_styler,
            ...{
}
        });

        function geo_json_2dfd0b3eb8d93a406e20399fe13c037e_add (data) {
            geo_json_2dfd0b3eb8d93a406e20399fe13c037e
                .addData(data);
        }
            geo_json_2dfd0b3eb8d93a406e20399fe13c037e_add({"features": [{"geometry": {"coordinates": [[-79.415512, 43.782425], [-79.381612, 43.839414], [-79.383285, 43.840189], [-79.385318, 43.842311], [-79.386364, 43.843154], [-79.382711, 43.84415], [-79.37832, 43.845217], [-79.364532, 43.848339], [-79.361786, 43.848961], [-79.35845, 43.849538], [-79.352661, 43.850916], [-79.346305, 43.852215], [-79.339497, 43.853825], [-79.338258, 43.852561], [-79.341119, 43.851765], [-79.344517, 43.851586]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_2dfd0b3eb8d93a406e20399fe13c037e.bindTooltip(
                `<div>
                     300 BUSINESS EXPRESS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_2dfd0b3eb8d93a406e20399fe13c037e.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_9d8b2ad895a49fbd16248f1f7c593f8f_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#8B0030", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_9d8b2ad895a49fbd16248f1f7c593f8f_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_9d8b2ad895a49fbd16248f1f7c593f8f = L.geoJson(null, {
                onEachFeature: geo_json_9d8b2ad895a49fbd16248f1f7c593f8f_onEachFeature,
            
                style: geo_json_9d8b2ad895a49fbd16248f1f7c593f8f_styler,
            ...{
}
        });

        function geo_json_9d8b2ad895a49fbd16248f1f7c593f8f_add (data) {
            geo_json_9d8b2ad895a49fbd16248f1f7c593f8f
                .addData(data);
        }
            geo_json_9d8b2ad895a49fbd16248f1f7c593f8f_add({"features": [{"geometry": {"coordinates": [[-79.344489, 43.851481], [-79.341141, 43.851553], [-79.338149, 43.85214], [-79.345806, 43.852697], [-79.351627, 43.851326], [-79.357736, 43.850185], [-79.360991, 43.849433], [-79.364169, 43.848691], [-79.377773, 43.845621], [-79.382009, 43.844696], [-79.386451, 43.842921], [-79.384588, 43.841869], [-79.38353, 43.84008], [-79.381316, 43.83931], [-79.415512, 43.782425]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_9d8b2ad895a49fbd16248f1f7c593f8f.bindTooltip(
                `<div>
                     300 BUSINESS EXPRESS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_9d8b2ad895a49fbd16248f1f7c593f8f.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_1e073d4b0383820c37f44106cad5e5fc_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#8B0030", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_1e073d4b0383820c37f44106cad5e5fc_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_1e073d4b0383820c37f44106cad5e5fc = L.geoJson(null, {
                onEachFeature: geo_json_1e073d4b0383820c37f44106cad5e5fc_onEachFeature,
            
                style: geo_json_1e073d4b0383820c37f44106cad5e5fc_styler,
            ...{
}
        });

        function geo_json_1e073d4b0383820c37f44106cad5e5fc_add (data) {
            geo_json_1e073d4b0383820c37f44106cad5e5fc
                .addData(data);
        }
            geo_json_1e073d4b0383820c37f44106cad5e5fc_add({"features": [{"geometry": {"coordinates": [[-79.364169, 43.848691], [-79.377773, 43.845621], [-79.382009, 43.844696], [-79.386451, 43.842921], [-79.384588, 43.841869], [-79.38353, 43.84008], [-79.381316, 43.83931], [-79.415512, 43.782425]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_1e073d4b0383820c37f44106cad5e5fc.bindTooltip(
                `<div>
                     300 BUSINESS EXPRESS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_1e073d4b0383820c37f44106cad5e5fc.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_678649ee6018cf4c670de543938a1758_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#8B0030", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_678649ee6018cf4c670de543938a1758_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_678649ee6018cf4c670de543938a1758 = L.geoJson(null, {
                onEachFeature: geo_json_678649ee6018cf4c670de543938a1758_onEachFeature,
            
                style: geo_json_678649ee6018cf4c670de543938a1758_styler,
            ...{
}
        });

        function geo_json_678649ee6018cf4c670de543938a1758_add (data) {
            geo_json_678649ee6018cf4c670de543938a1758
                .addData(data);
        }
            geo_json_678649ee6018cf4c670de543938a1758_add({"features": [{"geometry": {"coordinates": [[-79.381316, 43.83931], [-79.415512, 43.782425]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_678649ee6018cf4c670de543938a1758.bindTooltip(
                `<div>
                     300 BUSINESS EXPRESS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_678649ee6018cf4c670de543938a1758.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_aee30a1e99ab2ed197b36e120cf4082d_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0079C1", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_aee30a1e99ab2ed197b36e120cf4082d_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_aee30a1e99ab2ed197b36e120cf4082d = L.geoJson(null, {
                onEachFeature: geo_json_aee30a1e99ab2ed197b36e120cf4082d_onEachFeature,
            
                style: geo_json_aee30a1e99ab2ed197b36e120cf4082d_styler,
            ...{
}
        });

        function geo_json_aee30a1e99ab2ed197b36e120cf4082d_add (data) {
            geo_json_aee30a1e99ab2ed197b36e120cf4082d
                .addData(data);
        }
            geo_json_aee30a1e99ab2ed197b36e120cf4082d_add({"features": [{"geometry": {"coordinates": [[-79.263672, 43.900691], [-79.259173, 43.901802], [-79.256712, 43.898967], [-79.256135, 43.89687], [-79.255701, 43.894587], [-79.258399, 43.891934], [-79.257453, 43.891094], [-79.252466, 43.892278], [-79.249633, 43.892934], [-79.247579, 43.894262], [-79.24367, 43.895048], [-79.240594, 43.893638], [-79.240723, 43.891953], [-79.243497, 43.891258], [-79.246449, 43.890943], [-79.246025, 43.88845], [-79.245194, 43.886607], [-79.244604, 43.884361], [-79.24801, 43.883446], [-79.250424, 43.882953], [-79.253971, 43.883109], [-79.255327, 43.882811], [-79.259274, 43.881888], [-79.261446, 43.881347], [-79.263093, 43.88093], [-79.264333, 43.882031], [-79.265761, 43.883069], [-79.268827, 43.880904], [-79.271019, 43.879651], [-79.274921, 43.879111], [-79.277784, 43.879335], [-79.281904, 43.877843], [-79.28577, 43.877275], [-79.286547, 43.875043], [-79.286105, 43.872935], [-79.285414, 43.870054], [-79.284737, 43.867374], [-79.284126, 43.865022], [-79.283167, 43.861045], [-79.415512, 43.782425]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_aee30a1e99ab2ed197b36e120cf4082d.bindTooltip(
                `<div>
                     301 MARKHAM EXPRESS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_aee30a1e99ab2ed197b36e120cf4082d.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_10520f455eb7f932d124e46bb8aa92fd_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#0079C1", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_10520f455eb7f932d124e46bb8aa92fd_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_10520f455eb7f932d124e46bb8aa92fd = L.geoJson(null, {
                onEachFeature: geo_json_10520f455eb7f932d124e46bb8aa92fd_onEachFeature,
            
                style: geo_json_10520f455eb7f932d124e46bb8aa92fd_styler,
            ...{
}
        });

        function geo_json_10520f455eb7f932d124e46bb8aa92fd_add (data) {
            geo_json_10520f455eb7f932d124e46bb8aa92fd
                .addData(data);
        }
            geo_json_10520f455eb7f932d124e46bb8aa92fd_add({"features": [{"geometry": {"coordinates": [[-79.415512, 43.782425], [-79.282748, 43.860703], [-79.283912, 43.86546], [-79.284319, 43.866977], [-79.284976, 43.869598], [-79.285663, 43.872593], [-79.286102, 43.874173], [-79.286677, 43.876826], [-79.281812, 43.877745], [-79.278057, 43.879136], [-79.274712, 43.87888], [-79.271475, 43.879259], [-79.268484, 43.880929], [-79.266015, 43.882977], [-79.265986, 43.884474], [-79.266587, 43.887034], [-79.268164, 43.888858], [-79.270812, 43.888362], [-79.272837, 43.887903], [-79.273392, 43.888871], [-79.268945, 43.890163], [-79.264393, 43.891833], [-79.26276, 43.88599], [-79.261919, 43.882365], [-79.255739, 43.882583], [-79.253244, 43.883174], [-79.250786, 43.882867], [-79.247977, 43.883349], [-79.244582, 43.884151], [-79.244927, 43.886412], [-79.245553, 43.888068], [-79.246897, 43.890716], [-79.241514, 43.891636], [-79.24042, 43.893439], [-79.242867, 43.895348], [-79.246329, 43.894712], [-79.249146, 43.89317], [-79.253028, 43.892248], [-79.256783, 43.891363], [-79.258243, 43.891873], [-79.255583, 43.895019], [-79.256052, 43.896942], [-79.25669, 43.899243], [-79.263993, 43.900783]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_10520f455eb7f932d124e46bb8aa92fd.bindTooltip(
                `<div>
                     301 MARKHAM EXPRESS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_10520f455eb7f932d124e46bb8aa92fd.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_9a7f06b2e5da5ee7efd6ba177b33dd6e_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00B5CC", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_9a7f06b2e5da5ee7efd6ba177b33dd6e_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_9a7f06b2e5da5ee7efd6ba177b33dd6e = L.geoJson(null, {
                onEachFeature: geo_json_9a7f06b2e5da5ee7efd6ba177b33dd6e_onEachFeature,
            
                style: geo_json_9a7f06b2e5da5ee7efd6ba177b33dd6e_styler,
            ...{
}
        });

        function geo_json_9a7f06b2e5da5ee7efd6ba177b33dd6e_add (data) {
            geo_json_9a7f06b2e5da5ee7efd6ba177b33dd6e
                .addData(data);
        }
            geo_json_9a7f06b2e5da5ee7efd6ba177b33dd6e_add({"features": [{"geometry": {"coordinates": [[-79.339811, 43.855282], [-79.339349, 43.857519], [-79.340291, 43.860427], [-79.34433, 43.860392], [-79.348883, 43.859383], [-79.352628, 43.85855], [-79.355084, 43.86051], [-79.357371, 43.861822], [-79.358931, 43.864196], [-79.354747, 43.865665], [-79.353372, 43.866025], [-79.35088, 43.866816], [-79.348007, 43.867665], [-79.344074, 43.868138], [-79.342226, 43.867724], [-79.340341, 43.866707], [-79.33726, 43.867419], [-79.333086, 43.869915], [-79.32799, 43.870897], [-79.324121, 43.870995], [-79.320854, 43.871651], [-79.318459, 43.872183], [-79.316499, 43.871588], [-79.314253, 43.870154], [-79.31258, 43.868936], [-79.311395, 43.866209], [-79.31293, 43.865429], [-79.315651, 43.864479], [-79.318158, 43.863907], [-79.322528, 43.865464], [-79.326055, 43.864966], [-79.326193, 43.863634], [-79.329801, 43.86326], [-79.333283, 43.862332], [-79.333015, 43.860656], [-79.334075, 43.860161], [-79.334722, 43.85814], [-79.334172, 43.856002], [-79.333522, 43.853649], [-79.332221, 43.848745], [-79.415512, 43.782425]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_9a7f06b2e5da5ee7efd6ba177b33dd6e.bindTooltip(
                `<div>
                     302 UNIONVILLE EXPRESS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_9a7f06b2e5da5ee7efd6ba177b33dd6e.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_14095094a04b15078d1b24b8fb10825a_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00B5CC", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_14095094a04b15078d1b24b8fb10825a_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_14095094a04b15078d1b24b8fb10825a = L.geoJson(null, {
                onEachFeature: geo_json_14095094a04b15078d1b24b8fb10825a_onEachFeature,
            
                style: geo_json_14095094a04b15078d1b24b8fb10825a_styler,
            ...{
}
        });

        function geo_json_14095094a04b15078d1b24b8fb10825a_add (data) {
            geo_json_14095094a04b15078d1b24b8fb10825a
                .addData(data);
        }
            geo_json_14095094a04b15078d1b24b8fb10825a_add({"features": [{"geometry": {"coordinates": [[-79.415512, 43.782425], [-79.331627, 43.848329], [-79.334509, 43.853277], [-79.337831, 43.852532], [-79.338819, 43.85381], [-79.339811, 43.855282], [-79.339349, 43.857519], [-79.340291, 43.860427], [-79.34433, 43.860392], [-79.348883, 43.859383], [-79.352628, 43.85855], [-79.355084, 43.86051], [-79.357371, 43.861822], [-79.358931, 43.864196], [-79.354747, 43.865665], [-79.353372, 43.866025], [-79.35088, 43.866816], [-79.348007, 43.867665], [-79.344074, 43.868138], [-79.342226, 43.867724], [-79.340341, 43.866707], [-79.33726, 43.867419], [-79.333086, 43.869915], [-79.32799, 43.870897], [-79.324121, 43.870995], [-79.320854, 43.871651], [-79.318459, 43.872183], [-79.316499, 43.871588], [-79.314253, 43.870154], [-79.31258, 43.868936], [-79.311395, 43.866209], [-79.31293, 43.865429], [-79.315651, 43.864479], [-79.318158, 43.863907], [-79.322528, 43.865464], [-79.326055, 43.864966], [-79.326193, 43.863634], [-79.329801, 43.86326], [-79.333283, 43.862332], [-79.333015, 43.860656], [-79.334075, 43.860161], [-79.334722, 43.85814], [-79.334172, 43.856002]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_14095094a04b15078d1b24b8fb10825a.bindTooltip(
                `<div>
                     302 UNIONVILLE EXPRESS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_14095094a04b15078d1b24b8fb10825a.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_39dfdb7bc72a11338bafd4dfdadb52a5_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#702D03", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_39dfdb7bc72a11338bafd4dfdadb52a5_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_39dfdb7bc72a11338bafd4dfdadb52a5 = L.geoJson(null, {
                onEachFeature: geo_json_39dfdb7bc72a11338bafd4dfdadb52a5_onEachFeature,
            
                style: geo_json_39dfdb7bc72a11338bafd4dfdadb52a5_styler,
            ...{
}
        });

        function geo_json_39dfdb7bc72a11338bafd4dfdadb52a5_add (data) {
            geo_json_39dfdb7bc72a11338bafd4dfdadb52a5
                .addData(data);
        }
            geo_json_39dfdb7bc72a11338bafd4dfdadb52a5_add({"features": [{"geometry": {"coordinates": [[-79.263672, 43.900691], [-79.259173, 43.901802], [-79.255776, 43.902379], [-79.254047, 43.902596], [-79.249557, 43.902322], [-79.247642, 43.902198], [-79.244123, 43.902358], [-79.240989, 43.902247], [-79.239467, 43.902324], [-79.236009, 43.902684], [-79.232889, 43.902285], [-79.23155, 43.901479], [-79.231446, 43.899209], [-79.231798, 43.897471], [-79.231421, 43.895888], [-79.231637, 43.894166], [-79.231023, 43.891722], [-79.230522, 43.889773], [-79.230045, 43.888273], [-79.229593, 43.886669], [-79.229334, 43.885818], [-79.230203, 43.885522], [-79.233171, 43.884872], [-79.234428, 43.884572], [-79.235499, 43.880865], [-79.235086, 43.879252], [-79.234766, 43.878138], [-79.234261, 43.875921], [-79.415512, 43.782425]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_39dfdb7bc72a11338bafd4dfdadb52a5.bindTooltip(
                `<div>
                     303 BUR OAK EXPRESS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_39dfdb7bc72a11338bafd4dfdadb52a5.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_a61f70473c88da6eb70214d6e9980742_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#702D03", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_a61f70473c88da6eb70214d6e9980742_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_a61f70473c88da6eb70214d6e9980742 = L.geoJson(null, {
                onEachFeature: geo_json_a61f70473c88da6eb70214d6e9980742_onEachFeature,
            
                style: geo_json_a61f70473c88da6eb70214d6e9980742_styler,
            ...{
}
        });

        function geo_json_a61f70473c88da6eb70214d6e9980742_add (data) {
            geo_json_a61f70473c88da6eb70214d6e9980742
                .addData(data);
        }
            geo_json_a61f70473c88da6eb70214d6e9980742_add({"features": [{"geometry": {"coordinates": [[-79.415512, 43.782425], [-79.23386, 43.875474], [-79.234601, 43.878512], [-79.235156, 43.880494], [-79.235961, 43.883962], [-79.235234, 43.884241], [-79.23433, 43.884453], [-79.229955, 43.885504], [-79.229499, 43.886931], [-79.229819, 43.888092], [-79.230233, 43.889539], [-79.23086, 43.892056], [-79.23142, 43.894171], [-79.231086, 43.895559], [-79.231563, 43.897382], [-79.231663, 43.898272], [-79.231188, 43.901271], [-79.233463, 43.90254], [-79.235598, 43.902758], [-79.240356, 43.90244], [-79.241849, 43.902395], [-79.243703, 43.90246], [-79.247233, 43.902364], [-79.249689, 43.90247], [-79.253663, 43.902711], [-79.255492, 43.902497], [-79.258745, 43.902013], [-79.263993, 43.900783]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_a61f70473c88da6eb70214d6e9980742.bindTooltip(
                `<div>
                     303 BUR OAK EXPRESS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_a61f70473c88da6eb70214d6e9980742.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_14c300ff537a9eb2cf6bf36d36094119_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#702D03", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_14c300ff537a9eb2cf6bf36d36094119_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_14c300ff537a9eb2cf6bf36d36094119 = L.geoJson(null, {
                onEachFeature: geo_json_14c300ff537a9eb2cf6bf36d36094119_onEachFeature,
            
                style: geo_json_14c300ff537a9eb2cf6bf36d36094119_styler,
            ...{
}
        });

        function geo_json_14c300ff537a9eb2cf6bf36d36094119_add (data) {
            geo_json_14c300ff537a9eb2cf6bf36d36094119
                .addData(data);
        }
            geo_json_14c300ff537a9eb2cf6bf36d36094119_add({"features": [{"geometry": {"coordinates": [[-79.415666, 43.782573], [-79.23386, 43.875474], [-79.234601, 43.878512], [-79.235156, 43.880494], [-79.235961, 43.883962], [-79.235234, 43.884241], [-79.23433, 43.884453], [-79.229955, 43.885504], [-79.229499, 43.886931], [-79.229819, 43.888092], [-79.230233, 43.889539], [-79.23086, 43.892056], [-79.23142, 43.894171], [-79.231086, 43.895559], [-79.231563, 43.897382], [-79.231663, 43.898272], [-79.231188, 43.901271], [-79.233463, 43.90254], [-79.235598, 43.902758], [-79.240356, 43.90244], [-79.241849, 43.902395], [-79.243703, 43.90246], [-79.247233, 43.902364], [-79.249689, 43.90247], [-79.253663, 43.902711], [-79.255492, 43.902497], [-79.258745, 43.902013], [-79.263993, 43.900783]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_14c300ff537a9eb2cf6bf36d36094119.bindTooltip(
                `<div>
                     303 BUR OAK EXPRESS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_14c300ff537a9eb2cf6bf36d36094119.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_ef49ac89b0ac8110fe132c43093ea0c3_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#4C7520", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_ef49ac89b0ac8110fe132c43093ea0c3_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_ef49ac89b0ac8110fe132c43093ea0c3 = L.geoJson(null, {
                onEachFeature: geo_json_ef49ac89b0ac8110fe132c43093ea0c3_onEachFeature,
            
                style: geo_json_ef49ac89b0ac8110fe132c43093ea0c3_styler,
            ...{
}
        });

        function geo_json_ef49ac89b0ac8110fe132c43093ea0c3_add (data) {
            geo_json_ef49ac89b0ac8110fe132c43093ea0c3
                .addData(data);
        }
            geo_json_ef49ac89b0ac8110fe132c43093ea0c3_add({"features": [{"geometry": {"coordinates": [[-79.263993, 43.900783], [-79.265616, 43.900394], [-79.269085, 43.899854], [-79.271666, 43.899361], [-79.27512, 43.89872], [-79.275835, 43.898527], [-79.280051, 43.897616], [-79.28314, 43.89694], [-79.287415, 43.896036], [-79.290704, 43.894899], [-79.293171, 43.89455], [-79.296676, 43.894326], [-79.300991, 43.89355], [-79.303523, 43.892942], [-79.30507, 43.892145], [-79.305603, 43.89183], [-79.307722, 43.890708], [-79.309378, 43.890154], [-79.311703, 43.889605], [-79.313366, 43.889234], [-79.315923, 43.885384], [-79.31512, 43.882335], [-79.314525, 43.879725], [-79.313194, 43.876942], [-79.310302, 43.875764], [-79.306172, 43.872554], [-79.305333, 43.87022], [-79.304154, 43.866752], [-79.303634, 43.86215], [-79.302821, 43.859806], [-79.303326, 43.858309], [-79.305193, 43.856339], [-79.307873, 43.85615], [-79.322128, 43.85003], [-79.324507, 43.849467], [-79.329438, 43.849221], [-79.415512, 43.782425]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_ef49ac89b0ac8110fe132c43093ea0c3.bindTooltip(
                `<div>
                     304 MOUNT JOY EXPRESS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_ef49ac89b0ac8110fe132c43093ea0c3.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_3dcbe99221e73543b546b24604d946f0_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#4C7520", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_3dcbe99221e73543b546b24604d946f0_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_3dcbe99221e73543b546b24604d946f0 = L.geoJson(null, {
                onEachFeature: geo_json_3dcbe99221e73543b546b24604d946f0_onEachFeature,
            
                style: geo_json_3dcbe99221e73543b546b24604d946f0_styler,
            ...{
}
        });

        function geo_json_3dcbe99221e73543b546b24604d946f0_add (data) {
            geo_json_3dcbe99221e73543b546b24604d946f0
                .addData(data);
        }
            geo_json_3dcbe99221e73543b546b24604d946f0_add({"features": [{"geometry": {"coordinates": [[-79.415512, 43.782425], [-79.331627, 43.848329], [-79.329792, 43.848935], [-79.325096, 43.849135], [-79.321604, 43.849974], [-79.312364, 43.854312], [-79.308532, 43.855783], [-79.303456, 43.857799], [-79.302588, 43.859408], [-79.303396, 43.862411], [-79.303919, 43.866377], [-79.304843, 43.869851], [-79.306028, 43.872688], [-79.309673, 43.875844], [-79.312689, 43.876842], [-79.31419, 43.8799], [-79.314435, 43.881422], [-79.31543, 43.884984], [-79.316355, 43.888251], [-79.315666, 43.888557], [-79.312012, 43.889341], [-79.310452, 43.889737], [-79.307854, 43.890502], [-79.305836, 43.891548], [-79.303303, 43.892845], [-79.301346, 43.89335], [-79.298708, 43.893879], [-79.296969, 43.89412], [-79.29339, 43.894361], [-79.29145, 43.894616], [-79.287758, 43.895793], [-79.283614, 43.896732], [-79.279211, 43.897649], [-79.275559, 43.898488], [-79.271909, 43.899184], [-79.269391, 43.89966], [-79.266418, 43.90004], [-79.263672, 43.900691]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_3dcbe99221e73543b546b24604d946f0.bindTooltip(
                `<div>
                     304 MOUNT JOY EXPRESS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_3dcbe99221e73543b546b24604d946f0.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_afe32114653d03cbce363fb3d18f0add_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_afe32114653d03cbce363fb3d18f0add_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_afe32114653d03cbce363fb3d18f0add = L.geoJson(null, {
                onEachFeature: geo_json_afe32114653d03cbce363fb3d18f0add_onEachFeature,
            
                style: geo_json_afe32114653d03cbce363fb3d18f0add_styler,
            ...{
}
        });

        function geo_json_afe32114653d03cbce363fb3d18f0add_add (data) {
            geo_json_afe32114653d03cbce363fb3d18f0add
                .addData(data);
        }
            geo_json_afe32114653d03cbce363fb3d18f0add_add({"features": [{"geometry": {"coordinates": [[-79.212785, 43.869092], [-79.215888, 43.869834], [-79.220643, 43.870852], [-79.224298, 43.870037], [-79.228283, 43.867323], [-79.227634, 43.864694], [-79.2252, 43.86252], [-79.224469, 43.861015], [-79.223915, 43.85949], [-79.222375, 43.857421], [-79.225124, 43.856733], [-79.228948, 43.855739], [-79.229979, 43.85942], [-79.23722, 43.857921], [-79.238215, 43.855653], [-79.240491, 43.855191], [-79.243854, 43.856569], [-79.244391, 43.857888], [-79.246777, 43.858916], [-79.249965, 43.858667], [-79.250189, 43.856946], [-79.25245, 43.85628], [-79.255417, 43.856361], [-79.255643, 43.85673], [-79.256277, 43.859262], [-79.415512, 43.782425]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_afe32114653d03cbce363fb3d18f0add.bindTooltip(
                `<div>
                     305 BOX GROVE EXPRESS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_afe32114653d03cbce363fb3d18f0add.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_3d74101eee6bb1e7cda1475bbd6796d3_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_3d74101eee6bb1e7cda1475bbd6796d3_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_3d74101eee6bb1e7cda1475bbd6796d3 = L.geoJson(null, {
                onEachFeature: geo_json_3d74101eee6bb1e7cda1475bbd6796d3_onEachFeature,
            
                style: geo_json_3d74101eee6bb1e7cda1475bbd6796d3_styler,
            ...{
}
        });

        function geo_json_3d74101eee6bb1e7cda1475bbd6796d3_add (data) {
            geo_json_3d74101eee6bb1e7cda1475bbd6796d3
                .addData(data);
        }
            geo_json_3d74101eee6bb1e7cda1475bbd6796d3_add({"features": [{"geometry": {"coordinates": [[-79.415512, 43.782425], [-79.212785, 43.869092], [-79.215888, 43.869834], [-79.220643, 43.870852], [-79.224298, 43.870037], [-79.228283, 43.867323], [-79.227634, 43.864694], [-79.2252, 43.86252], [-79.224469, 43.861015], [-79.223915, 43.85949], [-79.222375, 43.857421], [-79.225124, 43.856733], [-79.228948, 43.855739], [-79.229979, 43.85942], [-79.23722, 43.857921], [-79.238215, 43.855653], [-79.240491, 43.855191], [-79.243854, 43.856569], [-79.244391, 43.857888], [-79.246777, 43.858916], [-79.249965, 43.858667], [-79.250189, 43.856946], [-79.25245, 43.85628], [-79.255417, 43.856361], [-79.255643, 43.85673], [-79.256277, 43.859262]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_3d74101eee6bb1e7cda1475bbd6796d3.bindTooltip(
                `<div>
                     305 BOX GROVE EXPRESS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_3d74101eee6bb1e7cda1475bbd6796d3.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_d3a9f8595bb5efa38febf2420fc4fd08_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_d3a9f8595bb5efa38febf2420fc4fd08_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_d3a9f8595bb5efa38febf2420fc4fd08 = L.geoJson(null, {
                onEachFeature: geo_json_d3a9f8595bb5efa38febf2420fc4fd08_onEachFeature,
            
                style: geo_json_d3a9f8595bb5efa38febf2420fc4fd08_styler,
            ...{
}
        });

        function geo_json_d3a9f8595bb5efa38febf2420fc4fd08_add (data) {
            geo_json_d3a9f8595bb5efa38febf2420fc4fd08
                .addData(data);
        }
            geo_json_d3a9f8595bb5efa38febf2420fc4fd08_add({"features": [{"geometry": {"coordinates": [[-79.415666, 43.782573], [-79.212785, 43.869092], [-79.215888, 43.869834], [-79.220643, 43.870852], [-79.224298, 43.870037], [-79.228283, 43.867323], [-79.227634, 43.864694], [-79.2252, 43.86252], [-79.224469, 43.861015], [-79.223915, 43.85949], [-79.222375, 43.857421], [-79.225124, 43.856733], [-79.228948, 43.855739], [-79.229979, 43.85942], [-79.23722, 43.857921], [-79.238215, 43.855653], [-79.240491, 43.855191], [-79.243854, 43.856569], [-79.244391, 43.857888], [-79.246777, 43.858916], [-79.249965, 43.858667], [-79.250189, 43.856946], [-79.25245, 43.85628], [-79.255417, 43.856361], [-79.255643, 43.85673], [-79.256277, 43.859262]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_d3a9f8595bb5efa38febf2420fc4fd08.bindTooltip(
                `<div>
                     305 BOX GROVE EXPRESS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_d3a9f8595bb5efa38febf2420fc4fd08.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_d6d7a0a3c0270a7556215e01835763be_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_d6d7a0a3c0270a7556215e01835763be_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_d6d7a0a3c0270a7556215e01835763be = L.geoJson(null, {
                onEachFeature: geo_json_d6d7a0a3c0270a7556215e01835763be_onEachFeature,
            
                style: geo_json_d6d7a0a3c0270a7556215e01835763be_styler,
            ...{
}
        });

        function geo_json_d6d7a0a3c0270a7556215e01835763be_add (data) {
            geo_json_d6d7a0a3c0270a7556215e01835763be
                .addData(data);
        }
            geo_json_d6d7a0a3c0270a7556215e01835763be_add({"features": [{"geometry": {"coordinates": [[-79.523079, 43.782521], [-79.527912, 43.796935], [-79.526392, 43.803755], [-79.528131, 43.812248], [-79.53379, 43.827129], [-79.535011, 43.842577], [-79.540771, 43.847416]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_d6d7a0a3c0270a7556215e01835763be.bindTooltip(
                `<div>
                     320 JANE EXPRESS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_d6d7a0a3c0270a7556215e01835763be.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_cd89c463dae9b71a3d64cb1de76708a2_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_cd89c463dae9b71a3d64cb1de76708a2_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_cd89c463dae9b71a3d64cb1de76708a2 = L.geoJson(null, {
                onEachFeature: geo_json_cd89c463dae9b71a3d64cb1de76708a2_onEachFeature,
            
                style: geo_json_cd89c463dae9b71a3d64cb1de76708a2_styler,
            ...{
}
        });

        function geo_json_cd89c463dae9b71a3d64cb1de76708a2_add (data) {
            geo_json_cd89c463dae9b71a3d64cb1de76708a2
                .addData(data);
        }
            geo_json_cd89c463dae9b71a3d64cb1de76708a2_add({"features": [{"geometry": {"coordinates": [[-79.540771, 43.847416], [-79.53543, 43.843215], [-79.533979, 43.827344], [-79.528471, 43.811871], [-79.526681, 43.803413], [-79.528383, 43.796736], [-79.523079, 43.782521]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_cd89c463dae9b71a3d64cb1de76708a2.bindTooltip(
                `<div>
                     320 JANE EXPRESS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_cd89c463dae9b71a3d64cb1de76708a2.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_2bc5f3bd6d28b30ec1925b339eea8c98_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_2bc5f3bd6d28b30ec1925b339eea8c98_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_2bc5f3bd6d28b30ec1925b339eea8c98 = L.geoJson(null, {
                onEachFeature: geo_json_2bc5f3bd6d28b30ec1925b339eea8c98_onEachFeature,
            
                style: geo_json_2bc5f3bd6d28b30ec1925b339eea8c98_styler,
            ...{
}
        });

        function geo_json_2bc5f3bd6d28b30ec1925b339eea8c98_add (data) {
            geo_json_2bc5f3bd6d28b30ec1925b339eea8c98
                .addData(data);
        }
            geo_json_2bc5f3bd6d28b30ec1925b339eea8c98_add({"features": [{"geometry": {"coordinates": [[-79.414632, 43.782515], [-79.416698, 43.78496], [-79.417335, 43.787532], [-79.417977, 43.790138], [-79.418316, 43.79149], [-79.418994, 43.794272], [-79.42011, 43.798695], [-79.420878, 43.801684], [-79.421756, 43.805238], [-79.422192, 43.807001], [-79.423127, 43.810912], [-79.42381, 43.814029], [-79.424299, 43.816215], [-79.425788, 43.822633], [-79.426318, 43.824924], [-79.426813, 43.827024], [-79.427303, 43.828884], [-79.427555, 43.830103], [-79.428022, 43.832324], [-79.429307, 43.838465], [-79.425239, 43.839817], [-79.541873, 43.821269], [-79.536888, 43.823275], [-79.534583, 43.827081], [-79.535011, 43.842577], [-79.541613, 43.847414]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_2bc5f3bd6d28b30ec1925b339eea8c98.bindTooltip(
                `<div>
                     360 VAUGHAN MILLS / WONDERLAND
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_2bc5f3bd6d28b30ec1925b339eea8c98.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_860a39313c0fc354dc2131a894fdd22c_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_860a39313c0fc354dc2131a894fdd22c_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_860a39313c0fc354dc2131a894fdd22c = L.geoJson(null, {
                onEachFeature: geo_json_860a39313c0fc354dc2131a894fdd22c_onEachFeature,
            
                style: geo_json_860a39313c0fc354dc2131a894fdd22c_styler,
            ...{
}
        });

        function geo_json_860a39313c0fc354dc2131a894fdd22c_add (data) {
            geo_json_860a39313c0fc354dc2131a894fdd22c
                .addData(data);
        }
            geo_json_860a39313c0fc354dc2131a894fdd22c_add({"features": [{"geometry": {"coordinates": [[-79.541613, 43.847414], [-79.53543, 43.843215], [-79.534583, 43.827081], [-79.537811, 43.823452], [-79.539431, 43.821994], [-79.425239, 43.839817], [-79.429701, 43.83824], [-79.429351, 43.836591], [-79.428506, 43.832738], [-79.42804, 43.83072], [-79.427575, 43.828851], [-79.427091, 43.826823], [-79.42672, 43.825278], [-79.426035, 43.822276], [-79.424704, 43.816482], [-79.424259, 43.814736], [-79.423491, 43.811126], [-79.422566, 43.807246], [-79.422211, 43.805597], [-79.4213, 43.802036], [-79.420274, 43.798244], [-79.420037, 43.797434], [-79.419718, 43.796088], [-79.419191, 43.793992], [-79.418625, 43.791289], [-79.418069, 43.789452], [-79.417496, 43.7872], [-79.414632, 43.782515]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_860a39313c0fc354dc2131a894fdd22c.bindTooltip(
                `<div>
                     360 VAUGHAN MILLS / WONDERLAND
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_860a39313c0fc354dc2131a894fdd22c.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_f7aa844350ca32142b72a4059cc2e187_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_f7aa844350ca32142b72a4059cc2e187_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_f7aa844350ca32142b72a4059cc2e187 = L.geoJson(null, {
                onEachFeature: geo_json_f7aa844350ca32142b72a4059cc2e187_onEachFeature,
            
                style: geo_json_f7aa844350ca32142b72a4059cc2e187_styler,
            ...{
}
        });

        function geo_json_f7aa844350ca32142b72a4059cc2e187_add (data) {
            geo_json_f7aa844350ca32142b72a4059cc2e187
                .addData(data);
        }
            geo_json_f7aa844350ca32142b72a4059cc2e187_add({"features": [{"geometry": {"coordinates": [[-79.523393, 43.782688], [-79.621513, 43.769438], [-79.62329, 43.76963], [-79.62519, 43.771936], [-79.626055, 43.774058], [-79.62643, 43.77598], [-79.627796, 43.776939], [-79.630304, 43.776843], [-79.639487, 43.775583], [-79.643614, 43.775295], [-79.644655, 43.77712], [-79.648493, 43.780088], [-79.650227, 43.783499], [-79.651336, 43.825518]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_f7aa844350ca32142b72a4059cc2e187.bindTooltip(
                `<div>
                     361 NASHVILLE EXPRESS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_f7aa844350ca32142b72a4059cc2e187.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_b3960e1293c8256684e01c765b824a2c_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_b3960e1293c8256684e01c765b824a2c_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_b3960e1293c8256684e01c765b824a2c = L.geoJson(null, {
                onEachFeature: geo_json_b3960e1293c8256684e01c765b824a2c_onEachFeature,
            
                style: geo_json_b3960e1293c8256684e01c765b824a2c_styler,
            ...{
}
        });

        function geo_json_b3960e1293c8256684e01c765b824a2c_add (data) {
            geo_json_b3960e1293c8256684e01c765b824a2c
                .addData(data);
        }
            geo_json_b3960e1293c8256684e01c765b824a2c_add({"features": [{"geometry": {"coordinates": [[-79.651336, 43.825518], [-79.651993, 43.827285], [-79.653741, 43.829109], [-79.655194, 43.830628], [-79.657323, 43.832996], [-79.65792, 43.834364], [-79.658895, 43.836544], [-79.659397, 43.837757], [-79.65773, 43.838443], [-79.655311, 43.838352], [-79.653637, 43.837342], [-79.650209, 43.833152], [-79.649658, 43.830865], [-79.651935, 43.827545], [-79.644117, 43.825302], [-79.631572, 43.8245], [-79.617241, 43.832014], [-79.614386, 43.830359], [-79.612229, 43.829158], [-79.609577, 43.826242], [-79.610178, 43.825882], [-79.613132, 43.824491], [-79.617759, 43.823545], [-79.621946, 43.822684], [-79.62572, 43.820004], [-79.625334, 43.81734], [-79.62398, 43.815947], [-79.620992, 43.814403], [-79.617851, 43.814666], [-79.61664, 43.813628], [-79.64975, 43.78106], [-79.648536, 43.779935], [-79.645616, 43.777645], [-79.639267, 43.775517], [-79.631194, 43.77664], [-79.626968, 43.776793], [-79.626318, 43.774255], [-79.626181, 43.773322], [-79.625407, 43.771452], [-79.621399, 43.769327], [-79.523393, 43.782688]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_b3960e1293c8256684e01c765b824a2c.bindTooltip(
                `<div>
                     361 NASHVILLE EXPRESS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_b3960e1293c8256684e01c765b824a2c.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_c30a7362d88bb262e0b6d67dd7496bc7_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_c30a7362d88bb262e0b6d67dd7496bc7_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_c30a7362d88bb262e0b6d67dd7496bc7 = L.geoJson(null, {
                onEachFeature: geo_json_c30a7362d88bb262e0b6d67dd7496bc7_onEachFeature,
            
                style: geo_json_c30a7362d88bb262e0b6d67dd7496bc7_styler,
            ...{
}
        });

        function geo_json_c30a7362d88bb262e0b6d67dd7496bc7_add (data) {
            geo_json_c30a7362d88bb262e0b6d67dd7496bc7
                .addData(data);
        }
            geo_json_c30a7362d88bb262e0b6d67dd7496bc7_add({"features": [{"geometry": {"coordinates": [[-79.422094, 43.900157], [-79.426044, 43.899903], [-79.426399, 43.901717], [-79.42626, 43.903032], [-79.422683, 43.903991], [-79.419986, 43.893855], [-79.419037, 43.889982], [-79.417865, 43.885392], [-79.416569, 43.880167], [-79.416026, 43.877896], [-79.415424, 43.875413], [-79.414715, 43.872415], [-79.413927, 43.869023], [-79.412405, 43.862989], [-79.411239, 43.858141], [-79.409795, 43.852127], [-79.408834, 43.848219], [-79.408127, 43.845365], [-79.415048, 43.782136]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_c30a7362d88bb262e0b6d67dd7496bc7.bindTooltip(
                `<div>
                     391 BAYVIEW EXPRESS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_c30a7362d88bb262e0b6d67dd7496bc7.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_a7e5810a915f1ae6506159a68ce50ee2_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_a7e5810a915f1ae6506159a68ce50ee2_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_a7e5810a915f1ae6506159a68ce50ee2 = L.geoJson(null, {
                onEachFeature: geo_json_a7e5810a915f1ae6506159a68ce50ee2_onEachFeature,
            
                style: geo_json_a7e5810a915f1ae6506159a68ce50ee2_styler,
            ...{
}
        });

        function geo_json_a7e5810a915f1ae6506159a68ce50ee2_add (data) {
            geo_json_a7e5810a915f1ae6506159a68ce50ee2
                .addData(data);
        }
            geo_json_a7e5810a915f1ae6506159a68ce50ee2_add({"features": [{"geometry": {"coordinates": [[-79.280212, 43.848974], [-79.276134, 43.850084], [-79.272163, 43.851001], [-79.268164, 43.851936], [-79.26306, 43.853139], [-79.258962, 43.854083], [-79.254995, 43.85625], [-79.251469, 43.856335], [-79.249599, 43.858584], [-79.247389, 43.858753], [-79.244804, 43.85819], [-79.243773, 43.856081], [-79.240725, 43.855013], [-79.237612, 43.855779], [-79.237012, 43.858498], [-79.233443, 43.860308], [-79.234956, 43.861714], [-79.240301, 43.861221], [-79.241925, 43.86341], [-79.242542, 43.865355], [-79.24047, 43.865741], [-79.234929, 43.865519], [-79.2328, 43.86463], [-79.23145, 43.863808], [-79.228887, 43.865279], [-79.227634, 43.864694], [-79.2252, 43.86252], [-79.222541, 43.861204], [-79.221793, 43.860784], [-79.221587, 43.858225], [-79.224071, 43.860605], [-79.224746, 43.86225], [-79.227079, 43.864747], [-79.230636, 43.865957], [-79.232671, 43.868936], [-79.23386, 43.875474], [-79.234601, 43.878512], [-79.229019, 43.878971], [-79.227385, 43.876962], [-79.231658, 43.87603], [-79.234601, 43.878512], [-79.235156, 43.880494], [-79.235961, 43.883962], [-79.235234, 43.884241], [-79.23433, 43.884453], [-79.232901, 43.884803], [-79.229955, 43.885504], [-79.229499, 43.886931], [-79.229819, 43.888092], [-79.230233, 43.889539], [-79.23086, 43.892056], [-79.23142, 43.894171], [-79.231086, 43.895559], [-79.228075, 43.895947], [-79.224863, 43.896285], [-79.221738, 43.896094], [-79.219941, 43.896313], [-79.220194, 43.898239], [-79.223811, 43.897842], [-79.22416, 43.898799], [-79.227524, 43.898885], [-79.231091, 43.899021], [-79.234841, 43.899132], [-79.240507, 43.8976], [-79.242724, 43.897133], [-79.245758, 43.89642], [-79.250078, 43.89538], [-79.255162, 43.894187], [-79.258402, 43.893399]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_a7e5810a915f1ae6506159a68ce50ee2.bindTooltip(
                `<div>
                     401 ST BROTHER ANDRE SS VIA BOX GROVE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_a7e5810a915f1ae6506159a68ce50ee2.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_de3fde845d5f4e02779827e855d48613_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_de3fde845d5f4e02779827e855d48613_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_de3fde845d5f4e02779827e855d48613 = L.geoJson(null, {
                onEachFeature: geo_json_de3fde845d5f4e02779827e855d48613_onEachFeature,
            
                style: geo_json_de3fde845d5f4e02779827e855d48613_styler,
            ...{
}
        });

        function geo_json_de3fde845d5f4e02779827e855d48613_add (data) {
            geo_json_de3fde845d5f4e02779827e855d48613
                .addData(data);
        }
            geo_json_de3fde845d5f4e02779827e855d48613_add({"features": [{"geometry": {"coordinates": [[-79.258838, 43.893121], [-79.255532, 43.893891], [-79.250827, 43.894936], [-79.246525, 43.896029], [-79.243039, 43.896828], [-79.239886, 43.897507], [-79.235337, 43.898737], [-79.231746, 43.898929], [-79.230692, 43.898631], [-79.228006, 43.898586], [-79.224785, 43.899332], [-79.222319, 43.89799], [-79.2204, 43.898265], [-79.219883, 43.896476], [-79.221459, 43.896189], [-79.224403, 43.896419], [-79.227667, 43.89606], [-79.231637, 43.894166], [-79.231023, 43.891722], [-79.230522, 43.889773], [-79.230045, 43.888273], [-79.229593, 43.886669], [-79.229334, 43.885818], [-79.230203, 43.885522], [-79.233171, 43.884872], [-79.234428, 43.884572], [-79.235499, 43.880865], [-79.235086, 43.879252], [-79.234766, 43.878138], [-79.231531, 43.875932], [-79.22746, 43.876717], [-79.228648, 43.878956], [-79.234766, 43.878138], [-79.234261, 43.875921], [-79.232566, 43.868316], [-79.229899, 43.865284], [-79.227634, 43.864694], [-79.2252, 43.86252], [-79.222541, 43.861204], [-79.221793, 43.860784], [-79.221587, 43.858225], [-79.224071, 43.860605], [-79.224746, 43.86225], [-79.227079, 43.864747], [-79.232257, 43.863842], [-79.232877, 43.864886], [-79.235645, 43.86577], [-79.240551, 43.865822], [-79.242494, 43.865525], [-79.242055, 43.863553], [-79.2401, 43.861056], [-79.235145, 43.861654], [-79.233822, 43.860387], [-79.23722, 43.857921], [-79.238215, 43.855653], [-79.240491, 43.855191], [-79.243854, 43.856569], [-79.244391, 43.857888], [-79.246777, 43.858916], [-79.249965, 43.858667], [-79.250189, 43.856946], [-79.25245, 43.85628], [-79.255417, 43.856361], [-79.258522, 43.854444], [-79.262234, 43.853479], [-79.267421, 43.852238], [-79.271502, 43.851311], [-79.275633, 43.850338], [-79.27932, 43.849447]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_de3fde845d5f4e02779827e855d48613.bindTooltip(
                `<div>
                     401 ST BROTHER ANDRE SS VIA BOX GROVE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_de3fde845d5f4e02779827e855d48613.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_d1799b4e1e021faaad78fc639b67b908_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_d1799b4e1e021faaad78fc639b67b908_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_d1799b4e1e021faaad78fc639b67b908 = L.geoJson(null, {
                onEachFeature: geo_json_d1799b4e1e021faaad78fc639b67b908_onEachFeature,
            
                style: geo_json_d1799b4e1e021faaad78fc639b67b908_styler,
            ...{
}
        });

        function geo_json_d1799b4e1e021faaad78fc639b67b908_add (data) {
            geo_json_d1799b4e1e021faaad78fc639b67b908
                .addData(data);
        }
            geo_json_d1799b4e1e021faaad78fc639b67b908_add({"features": [{"geometry": {"coordinates": [[-79.234428, 43.884572], [-79.235499, 43.880865], [-79.235086, 43.879252], [-79.234766, 43.878138], [-79.231531, 43.875932], [-79.22746, 43.876717], [-79.228648, 43.878956], [-79.225589, 43.880425], [-79.227727, 43.884372], [-79.229499, 43.886931], [-79.229819, 43.888092], [-79.230233, 43.889539], [-79.23086, 43.892056], [-79.23142, 43.894171], [-79.231086, 43.895559], [-79.228075, 43.895947], [-79.224863, 43.896285], [-79.221738, 43.896094], [-79.219941, 43.896313], [-79.220194, 43.898239], [-79.223811, 43.897842], [-79.22416, 43.898799], [-79.227524, 43.898885], [-79.231091, 43.899021], [-79.231188, 43.901271], [-79.233463, 43.90254], [-79.235598, 43.902758], [-79.240356, 43.90244], [-79.241849, 43.902395], [-79.243703, 43.90246], [-79.247233, 43.902364], [-79.249689, 43.90247], [-79.253663, 43.902711], [-79.255492, 43.902497], [-79.258745, 43.902013], [-79.263993, 43.900783], [-79.265616, 43.900394], [-79.269085, 43.899854], [-79.271666, 43.899361], [-79.27512, 43.89872], [-79.275835, 43.898527], [-79.280051, 43.897616], [-79.28314, 43.89694], [-79.287415, 43.896036], [-79.290704, 43.894899], [-79.293171, 43.89455], [-79.296676, 43.894326], [-79.300991, 43.89355], [-79.303523, 43.892942], [-79.30507, 43.892145], [-79.305603, 43.89183], [-79.307722, 43.890708], [-79.309378, 43.890154], [-79.311703, 43.889605], [-79.313366, 43.889234], [-79.316297, 43.888608], [-79.317227, 43.891357], [-79.317779, 43.893878], [-79.333537, 43.894416], [-79.336632, 43.893695], [-79.337417, 43.894645]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_d1799b4e1e021faaad78fc639b67b908.bindTooltip(
                `<div>
                     402 BUR OAK / PIERRE ELLIOTT TRUDEAU SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_d1799b4e1e021faaad78fc639b67b908.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_305fd350fa0945ba576cdea07da5cb5f_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_305fd350fa0945ba576cdea07da5cb5f_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_305fd350fa0945ba576cdea07da5cb5f = L.geoJson(null, {
                onEachFeature: geo_json_305fd350fa0945ba576cdea07da5cb5f_onEachFeature,
            
                style: geo_json_305fd350fa0945ba576cdea07da5cb5f_styler,
            ...{
}
        });

        function geo_json_305fd350fa0945ba576cdea07da5cb5f_add (data) {
            geo_json_305fd350fa0945ba576cdea07da5cb5f
                .addData(data);
        }
            geo_json_305fd350fa0945ba576cdea07da5cb5f_add({"features": [{"geometry": {"coordinates": [[-79.337417, 43.894645], [-79.321227, 43.89695], [-79.319462, 43.897339], [-79.318684, 43.896336], [-79.318239, 43.894256], [-79.317552, 43.891385], [-79.315666, 43.888557], [-79.312012, 43.889341], [-79.310452, 43.889737], [-79.307854, 43.890502], [-79.305836, 43.891548], [-79.303303, 43.892845], [-79.301346, 43.89335], [-79.298708, 43.893879], [-79.296969, 43.89412], [-79.29339, 43.894361], [-79.29145, 43.894616], [-79.287758, 43.895793], [-79.283614, 43.896732], [-79.279211, 43.897649], [-79.275559, 43.898488], [-79.271909, 43.899184], [-79.269391, 43.89966], [-79.266418, 43.90004], [-79.263672, 43.900691], [-79.259173, 43.901802], [-79.255776, 43.902379], [-79.254047, 43.902596], [-79.249557, 43.902322], [-79.247642, 43.902198], [-79.244123, 43.902358], [-79.240989, 43.902247], [-79.239467, 43.902324], [-79.236009, 43.902684], [-79.232889, 43.902285], [-79.23155, 43.901479], [-79.230692, 43.898631], [-79.228006, 43.898586], [-79.224785, 43.899332], [-79.224368, 43.899053], [-79.222319, 43.89799], [-79.2204, 43.898265], [-79.219883, 43.896476], [-79.221459, 43.896189], [-79.223223, 43.896422], [-79.224403, 43.896419], [-79.227667, 43.89606], [-79.231637, 43.894166], [-79.231023, 43.891722], [-79.230522, 43.889773], [-79.230045, 43.888273], [-79.229593, 43.886669], [-79.229334, 43.885818], [-79.230203, 43.885522], [-79.233171, 43.884872], [-79.234428, 43.884572], [-79.235499, 43.880865], [-79.229019, 43.878971], [-79.227385, 43.876962], [-79.231658, 43.87603]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_305fd350fa0945ba576cdea07da5cb5f.bindTooltip(
                `<div>
                     402 BUR OAK / PIERRE ELLIOTT TRUDEAU SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_305fd350fa0945ba576cdea07da5cb5f.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_e0f135e807e80f5ae4bcfc94fd989112_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_e0f135e807e80f5ae4bcfc94fd989112_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_e0f135e807e80f5ae4bcfc94fd989112 = L.geoJson(null, {
                onEachFeature: geo_json_e0f135e807e80f5ae4bcfc94fd989112_onEachFeature,
            
                style: geo_json_e0f135e807e80f5ae4bcfc94fd989112_styler,
            ...{
}
        });

        function geo_json_e0f135e807e80f5ae4bcfc94fd989112_add (data) {
            geo_json_e0f135e807e80f5ae4bcfc94fd989112
                .addData(data);
        }
            geo_json_e0f135e807e80f5ae4bcfc94fd989112_add({"features": [{"geometry": {"coordinates": [[-79.279211, 43.897649], [-79.275559, 43.898488], [-79.271909, 43.899184], [-79.269391, 43.89966], [-79.266418, 43.90004], [-79.263672, 43.900691], [-79.259173, 43.901802], [-79.255776, 43.902379], [-79.254047, 43.902596], [-79.249557, 43.902322], [-79.247642, 43.902198], [-79.244123, 43.902358], [-79.240989, 43.902247], [-79.239467, 43.902324], [-79.236009, 43.902684], [-79.232889, 43.902285], [-79.23155, 43.901479], [-79.230692, 43.898631], [-79.228006, 43.898586], [-79.224785, 43.899332], [-79.224368, 43.899053], [-79.222319, 43.89799], [-79.2204, 43.898265], [-79.219883, 43.896476], [-79.221459, 43.896189], [-79.223223, 43.896422], [-79.224403, 43.896419], [-79.227667, 43.89606], [-79.231637, 43.894166], [-79.231023, 43.891722], [-79.230522, 43.889773], [-79.230045, 43.888273], [-79.229593, 43.886669], [-79.229334, 43.885818], [-79.230203, 43.885522], [-79.233171, 43.884872], [-79.234428, 43.884572], [-79.235499, 43.880865], [-79.229019, 43.878971], [-79.227385, 43.876962], [-79.231658, 43.87603]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_e0f135e807e80f5ae4bcfc94fd989112.bindTooltip(
                `<div>
                     402 BUR OAK / PIERRE ELLIOTT TRUDEAU SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_e0f135e807e80f5ae4bcfc94fd989112.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_6f7a474ad0eefaf0d547cf000649ccbf_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_6f7a474ad0eefaf0d547cf000649ccbf_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_6f7a474ad0eefaf0d547cf000649ccbf = L.geoJson(null, {
                onEachFeature: geo_json_6f7a474ad0eefaf0d547cf000649ccbf_onEachFeature,
            
                style: geo_json_6f7a474ad0eefaf0d547cf000649ccbf_styler,
            ...{
}
        });

        function geo_json_6f7a474ad0eefaf0d547cf000649ccbf_add (data) {
            geo_json_6f7a474ad0eefaf0d547cf000649ccbf
                .addData(data);
        }
            geo_json_6f7a474ad0eefaf0d547cf000649ccbf_add({"features": [{"geometry": {"coordinates": [[-79.28813, 43.867088], [-79.284976, 43.869598], [-79.285663, 43.872593], [-79.286102, 43.874173], [-79.286677, 43.876826], [-79.281812, 43.877745], [-79.278057, 43.879136], [-79.274712, 43.87888], [-79.271475, 43.879259], [-79.268484, 43.880929], [-79.266015, 43.882977], [-79.265986, 43.884474], [-79.266587, 43.887034], [-79.268164, 43.888858], [-79.270812, 43.888362], [-79.272837, 43.887903], [-79.273392, 43.888871], [-79.268945, 43.890163], [-79.264393, 43.891833], [-79.258838, 43.893121], [-79.258399, 43.891934], [-79.257453, 43.891094], [-79.252466, 43.892278], [-79.249633, 43.892934], [-79.247579, 43.894262], [-79.24367, 43.895048], [-79.240594, 43.893638], [-79.240723, 43.891953], [-79.243497, 43.891258], [-79.246449, 43.890943], [-79.246025, 43.88845], [-79.245194, 43.886607], [-79.244604, 43.884361], [-79.24801, 43.883446], [-79.250424, 43.882953], [-79.253971, 43.883109], [-79.255327, 43.882811], [-79.259274, 43.881888], [-79.261446, 43.881347], [-79.26182, 43.882874], [-79.262477, 43.885556], [-79.26389, 43.891874], [-79.258838, 43.893121]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_6f7a474ad0eefaf0d547cf000649ccbf.bindTooltip(
                `<div>
                     403 ST BROTHER ANDRE SS VIA RAYMERVILLE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_6f7a474ad0eefaf0d547cf000649ccbf.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_09eaa70a45806686bf9ced8f0cc0c0bf_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_09eaa70a45806686bf9ced8f0cc0c0bf_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_09eaa70a45806686bf9ced8f0cc0c0bf = L.geoJson(null, {
                onEachFeature: geo_json_09eaa70a45806686bf9ced8f0cc0c0bf_onEachFeature,
            
                style: geo_json_09eaa70a45806686bf9ced8f0cc0c0bf_styler,
            ...{
}
        });

        function geo_json_09eaa70a45806686bf9ced8f0cc0c0bf_add (data) {
            geo_json_09eaa70a45806686bf9ced8f0cc0c0bf
                .addData(data);
        }
            geo_json_09eaa70a45806686bf9ced8f0cc0c0bf_add({"features": [{"geometry": {"coordinates": [[-79.258838, 43.893121], [-79.258399, 43.891934], [-79.257453, 43.891094], [-79.252466, 43.892278], [-79.249633, 43.892934], [-79.247579, 43.894262], [-79.24367, 43.895048], [-79.240594, 43.893638], [-79.240723, 43.891953], [-79.243497, 43.891258], [-79.246449, 43.890943], [-79.246025, 43.88845], [-79.245194, 43.886607], [-79.244604, 43.884361], [-79.24801, 43.883446], [-79.250424, 43.882953], [-79.253971, 43.883109], [-79.255327, 43.882811], [-79.259274, 43.881888], [-79.261446, 43.881347], [-79.263093, 43.88093], [-79.264333, 43.882031], [-79.265761, 43.883069], [-79.265986, 43.884474], [-79.266587, 43.887034], [-79.268164, 43.888858], [-79.270812, 43.888362], [-79.272837, 43.887903], [-79.273392, 43.888871], [-79.268945, 43.890163], [-79.264393, 43.891833], [-79.26276, 43.88599], [-79.261919, 43.882365], [-79.261685, 43.881363], [-79.263093, 43.88093], [-79.264333, 43.882031], [-79.265761, 43.883069], [-79.268827, 43.880904], [-79.271019, 43.879651], [-79.274921, 43.879111], [-79.277784, 43.879335], [-79.281904, 43.877843], [-79.28577, 43.877275], [-79.286547, 43.875043], [-79.286105, 43.872935], [-79.285414, 43.870054], [-79.284737, 43.867374], [-79.28813, 43.867088]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_09eaa70a45806686bf9ced8f0cc0c0bf.bindTooltip(
                `<div>
                     403 ST BROTHER ANDRE SS VIA RAYMERVILLE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_09eaa70a45806686bf9ced8f0cc0c0bf.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_98348965c38d033b6fc8aec7192e910d_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_98348965c38d033b6fc8aec7192e910d_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_98348965c38d033b6fc8aec7192e910d = L.geoJson(null, {
                onEachFeature: geo_json_98348965c38d033b6fc8aec7192e910d_onEachFeature,
            
                style: geo_json_98348965c38d033b6fc8aec7192e910d_styler,
            ...{
}
        });

        function geo_json_98348965c38d033b6fc8aec7192e910d_add (data) {
            geo_json_98348965c38d033b6fc8aec7192e910d
                .addData(data);
        }
            geo_json_98348965c38d033b6fc8aec7192e910d_add({"features": [{"geometry": {"coordinates": [[-79.302183, 43.85436], [-79.300508, 43.85576], [-79.297798, 43.856403], [-79.296422, 43.858472], [-79.293164, 43.859407], [-79.289682, 43.861203], [-79.286998, 43.85998], [-79.284062, 43.860542], [-79.283912, 43.86546], [-79.284319, 43.866977], [-79.284976, 43.869598], [-79.285663, 43.872593], [-79.286102, 43.874173], [-79.289463, 43.876546]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_98348965c38d033b6fc8aec7192e910d.bindTooltip(
                `<div>
                     404 MARKVILLE SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_98348965c38d033b6fc8aec7192e910d.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_412f1bca0e439e7d73b53d845c490ae5_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_412f1bca0e439e7d73b53d845c490ae5_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_412f1bca0e439e7d73b53d845c490ae5 = L.geoJson(null, {
                onEachFeature: geo_json_412f1bca0e439e7d73b53d845c490ae5_onEachFeature,
            
                style: geo_json_412f1bca0e439e7d73b53d845c490ae5_styler,
            ...{
}
        });

        function geo_json_412f1bca0e439e7d73b53d845c490ae5_add (data) {
            geo_json_412f1bca0e439e7d73b53d845c490ae5
                .addData(data);
        }
            geo_json_412f1bca0e439e7d73b53d845c490ae5_add({"features": [{"geometry": {"coordinates": [[-79.287177, 43.876898], [-79.286547, 43.875043], [-79.286105, 43.872935], [-79.285414, 43.870054], [-79.284737, 43.867374], [-79.284126, 43.865022], [-79.283167, 43.861045], [-79.286031, 43.860216], [-79.289073, 43.860587], [-79.293768, 43.859118], [-79.296061, 43.858627], [-79.29712, 43.856767], [-79.299866, 43.856013], [-79.30159, 43.854657]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_412f1bca0e439e7d73b53d845c490ae5.bindTooltip(
                `<div>
                     404 MARKVILLE SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_412f1bca0e439e7d73b53d845c490ae5.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_706ebda00dfb8a5c695c98543071ff4a_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_706ebda00dfb8a5c695c98543071ff4a_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_706ebda00dfb8a5c695c98543071ff4a = L.geoJson(null, {
                onEachFeature: geo_json_706ebda00dfb8a5c695c98543071ff4a_onEachFeature,
            
                style: geo_json_706ebda00dfb8a5c695c98543071ff4a_styler,
            ...{
}
        });

        function geo_json_706ebda00dfb8a5c695c98543071ff4a_add (data) {
            geo_json_706ebda00dfb8a5c695c98543071ff4a
                .addData(data);
        }
            geo_json_706ebda00dfb8a5c695c98543071ff4a_add({"features": [{"geometry": {"coordinates": [[-79.28813, 43.867088], [-79.284976, 43.869598], [-79.285663, 43.872593], [-79.286102, 43.874173], [-79.289463, 43.876546], [-79.291537, 43.875804], [-79.2975, 43.874183], [-79.298981, 43.872615], [-79.300576, 43.871157], [-79.304738, 43.870237], [-79.309549, 43.869119], [-79.312073, 43.868926], [-79.313612, 43.869788], [-79.316283, 43.871618], [-79.318583, 43.872267], [-79.32192, 43.871533], [-79.323572, 43.871186], [-79.328063, 43.870994], [-79.328023, 43.867853], [-79.326818, 43.865813], [-79.326193, 43.863634], [-79.329801, 43.86326], [-79.333283, 43.862332], [-79.333015, 43.860656], [-79.334075, 43.860161], [-79.334722, 43.85814], [-79.334172, 43.856002], [-79.339009, 43.854388], [-79.339811, 43.855282], [-79.339349, 43.857519], [-79.338642, 43.85988], [-79.338482, 43.86158], [-79.339522, 43.864592], [-79.340041, 43.866439], [-79.34182, 43.867767], [-79.343789, 43.868159], [-79.347602, 43.867986], [-79.349411, 43.867433], [-79.352386, 43.86993], [-79.35487, 43.871832], [-79.355758, 43.872918], [-79.356843, 43.874324], [-79.358228, 43.876278], [-79.360937, 43.877293], [-79.364163, 43.876995]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_706ebda00dfb8a5c695c98543071ff4a.bindTooltip(
                `<div>
                     405 ST AUGUSTINE SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_706ebda00dfb8a5c695c98543071ff4a.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_2b8d5bae34bec03241ecf3453a660ae9_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_2b8d5bae34bec03241ecf3453a660ae9_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_2b8d5bae34bec03241ecf3453a660ae9 = L.geoJson(null, {
                onEachFeature: geo_json_2b8d5bae34bec03241ecf3453a660ae9_onEachFeature,
            
                style: geo_json_2b8d5bae34bec03241ecf3453a660ae9_styler,
            ...{
}
        });

        function geo_json_2b8d5bae34bec03241ecf3453a660ae9_add (data) {
            geo_json_2b8d5bae34bec03241ecf3453a660ae9
                .addData(data);
        }
            geo_json_2b8d5bae34bec03241ecf3453a660ae9_add({"features": [{"geometry": {"coordinates": [[-79.364004, 43.876817], [-79.362234, 43.87708], [-79.360496, 43.877173], [-79.358776, 43.876642], [-79.357482, 43.874949], [-79.356229, 43.873223], [-79.355096, 43.871826], [-79.352846, 43.870326], [-79.350799, 43.867086], [-79.352495, 43.866379], [-79.356051, 43.86549], [-79.358915, 43.864439], [-79.357361, 43.861652], [-79.355642, 43.860756], [-79.353224, 43.85907], [-79.349392, 43.859099], [-79.344633, 43.860163], [-79.342172, 43.860386], [-79.339074, 43.860084], [-79.339541, 43.857864], [-79.339915, 43.854869], [-79.334236, 43.857664], [-79.334751, 43.859694], [-79.332993, 43.86033], [-79.333338, 43.862107], [-79.329693, 43.86314], [-79.326341, 43.863429], [-79.326258, 43.865153], [-79.327956, 43.8682], [-79.32799, 43.870897], [-79.324121, 43.870995], [-79.320854, 43.871651], [-79.318459, 43.872183], [-79.316499, 43.871588], [-79.314253, 43.870154], [-79.31258, 43.868936], [-79.309346, 43.869029], [-79.305361, 43.869885], [-79.300928, 43.870907], [-79.299012, 43.87234], [-79.297536, 43.873966], [-79.291864, 43.875576], [-79.287177, 43.876898], [-79.286547, 43.875043], [-79.286105, 43.872935], [-79.285414, 43.870054], [-79.284737, 43.867374], [-79.28813, 43.867088]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_2b8d5bae34bec03241ecf3453a660ae9.bindTooltip(
                `<div>
                     405 ST AUGUSTINE SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_2b8d5bae34bec03241ecf3453a660ae9.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_0cff65fb536d5874aadd2bb2ac1c592c_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_0cff65fb536d5874aadd2bb2ac1c592c_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_0cff65fb536d5874aadd2bb2ac1c592c = L.geoJson(null, {
                onEachFeature: geo_json_0cff65fb536d5874aadd2bb2ac1c592c_onEachFeature,
            
                style: geo_json_0cff65fb536d5874aadd2bb2ac1c592c_styler,
            ...{
}
        });

        function geo_json_0cff65fb536d5874aadd2bb2ac1c592c_add (data) {
            geo_json_0cff65fb536d5874aadd2bb2ac1c592c
                .addData(data);
        }
            geo_json_0cff65fb536d5874aadd2bb2ac1c592c_add({"features": [{"geometry": {"coordinates": [[-79.220874, 43.884107], [-79.218168, 43.885793], [-79.218709, 43.887843], [-79.220213, 43.89105], [-79.219337, 43.893314], [-79.219657, 43.89618], [-79.221459, 43.896189], [-79.223223, 43.896422], [-79.224403, 43.896419], [-79.227667, 43.89606], [-79.231637, 43.894166], [-79.231023, 43.891722], [-79.230522, 43.889773], [-79.230045, 43.888273], [-79.229593, 43.886669], [-79.229334, 43.885818], [-79.230203, 43.885522], [-79.233171, 43.884872], [-79.234428, 43.884572], [-79.240721, 43.883096], [-79.243408, 43.882443], [-79.244328, 43.884115], [-79.24801, 43.883446], [-79.250424, 43.882953], [-79.253971, 43.883109], [-79.255327, 43.882811], [-79.25103, 43.880567]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_0cff65fb536d5874aadd2bb2ac1c592c.bindTooltip(
                `<div>
                     406 MARKHAM DISTRICT SS VIA BUR OAK
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_0cff65fb536d5874aadd2bb2ac1c592c.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_43f0212cd4e704577c6a6b742336f021_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_43f0212cd4e704577c6a6b742336f021_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_43f0212cd4e704577c6a6b742336f021 = L.geoJson(null, {
                onEachFeature: geo_json_43f0212cd4e704577c6a6b742336f021_onEachFeature,
            
                style: geo_json_43f0212cd4e704577c6a6b742336f021_styler,
            ...{
}
        });

        function geo_json_43f0212cd4e704577c6a6b742336f021_add (data) {
            geo_json_43f0212cd4e704577c6a6b742336f021
                .addData(data);
        }
            geo_json_43f0212cd4e704577c6a6b742336f021_add({"features": [{"geometry": {"coordinates": [[-79.25103, 43.880567], [-79.243745, 43.882287], [-79.240992, 43.882924], [-79.235234, 43.884241], [-79.23433, 43.884453], [-79.232901, 43.884803], [-79.229955, 43.885504], [-79.229499, 43.886931], [-79.229819, 43.888092], [-79.230233, 43.889539], [-79.23086, 43.892056], [-79.23142, 43.894171], [-79.231086, 43.895559], [-79.228075, 43.895947], [-79.224863, 43.896285], [-79.221738, 43.896094], [-79.219941, 43.896313], [-79.219388, 43.893579], [-79.220447, 43.891256], [-79.219002, 43.888137], [-79.218388, 43.885948], [-79.22073, 43.884324]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_43f0212cd4e704577c6a6b742336f021.bindTooltip(
                `<div>
                     406 MARKHAM DISTRICT SS VIA BUR OAK
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_43f0212cd4e704577c6a6b742336f021.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_ed11d1c1dd43e9e0519ad90a5e5d64de_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_ed11d1c1dd43e9e0519ad90a5e5d64de_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_ed11d1c1dd43e9e0519ad90a5e5d64de = L.geoJson(null, {
                onEachFeature: geo_json_ed11d1c1dd43e9e0519ad90a5e5d64de_onEachFeature,
            
                style: geo_json_ed11d1c1dd43e9e0519ad90a5e5d64de_styler,
            ...{
}
        });

        function geo_json_ed11d1c1dd43e9e0519ad90a5e5d64de_add (data) {
            geo_json_ed11d1c1dd43e9e0519ad90a5e5d64de
                .addData(data);
        }
            geo_json_ed11d1c1dd43e9e0519ad90a5e5d64de_add({"features": [{"geometry": {"coordinates": [[-79.417865, 43.885392], [-79.417259, 43.882953], [-79.416569, 43.880167], [-79.416026, 43.877896], [-79.415424, 43.875413], [-79.414715, 43.872415], [-79.413927, 43.869023], [-79.413427, 43.867023], [-79.412405, 43.862989], [-79.411969, 43.861189], [-79.411239, 43.858141], [-79.410691, 43.856002], [-79.410168, 43.853831], [-79.409795, 43.852127], [-79.408834, 43.848219], [-79.408127, 43.845365], [-79.409187, 43.844984], [-79.411308, 43.844197], [-79.414573, 43.843036], [-79.416281, 43.842809], [-79.41975, 43.842683], [-79.422957, 43.841393], [-79.421021, 43.839908], [-79.42523, 43.839711]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_ed11d1c1dd43e9e0519ad90a5e5d64de.bindTooltip(
                `<div>
                     408 OUR LADY QUEEN OF THE WORLD SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_ed11d1c1dd43e9e0519ad90a5e5d64de.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_4d5e6050bfd8e736437f7f503e556249_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_4d5e6050bfd8e736437f7f503e556249_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_4d5e6050bfd8e736437f7f503e556249 = L.geoJson(null, {
                onEachFeature: geo_json_4d5e6050bfd8e736437f7f503e556249_onEachFeature,
            
                style: geo_json_4d5e6050bfd8e736437f7f503e556249_styler,
            ...{
}
        });

        function geo_json_4d5e6050bfd8e736437f7f503e556249_add (data) {
            geo_json_4d5e6050bfd8e736437f7f503e556249
                .addData(data);
        }
            geo_json_4d5e6050bfd8e736437f7f503e556249_add({"features": [{"geometry": {"coordinates": [[-79.364737, 43.876569], [-79.364004, 43.876817], [-79.362234, 43.87708], [-79.360496, 43.877173], [-79.358776, 43.876642], [-79.357482, 43.874949], [-79.356229, 43.873223], [-79.355096, 43.871826], [-79.352846, 43.870326], [-79.350799, 43.867086], [-79.348007, 43.867665], [-79.344074, 43.868138], [-79.342226, 43.867724], [-79.340341, 43.866707], [-79.339732, 43.864809], [-79.338697, 43.861735], [-79.33599, 43.859693], [-79.332993, 43.86033], [-79.333338, 43.862107], [-79.329693, 43.86314], [-79.326341, 43.863429], [-79.326258, 43.865153], [-79.327956, 43.8682], [-79.32799, 43.870897], [-79.324121, 43.870995], [-79.320854, 43.871651], [-79.318459, 43.872183], [-79.316499, 43.871588], [-79.314253, 43.870154], [-79.31258, 43.868936], [-79.309346, 43.869029], [-79.305361, 43.869885], [-79.300928, 43.870907], [-79.299012, 43.87234], [-79.297536, 43.873966], [-79.291864, 43.875576], [-79.287177, 43.876898], [-79.281812, 43.877745], [-79.278057, 43.879136], [-79.274712, 43.87888], [-79.271475, 43.879259], [-79.268484, 43.880929], [-79.266015, 43.882977], [-79.265986, 43.884474], [-79.266587, 43.887034], [-79.268164, 43.888858], [-79.270812, 43.888362], [-79.272837, 43.887903], [-79.273392, 43.888871], [-79.268945, 43.890163], [-79.264393, 43.891833], [-79.258838, 43.893121], [-79.257453, 43.891094], [-79.252466, 43.892278], [-79.249633, 43.892934], [-79.247579, 43.894262], [-79.24367, 43.895048], [-79.240594, 43.893638], [-79.240723, 43.891953], [-79.243497, 43.891258], [-79.246449, 43.890943], [-79.246025, 43.88845], [-79.245194, 43.886607], [-79.244604, 43.884361], [-79.24801, 43.883446], [-79.250424, 43.882953], [-79.253971, 43.883109], [-79.255327, 43.882811], [-79.25103, 43.880567]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_4d5e6050bfd8e736437f7f503e556249.bindTooltip(
                `<div>
                     410 MARKHAM DISTRICT SS VIA CARLTON
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_4d5e6050bfd8e736437f7f503e556249.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_1d21747c840786d83430ecb65cba9508_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_1d21747c840786d83430ecb65cba9508_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_1d21747c840786d83430ecb65cba9508 = L.geoJson(null, {
                onEachFeature: geo_json_1d21747c840786d83430ecb65cba9508_onEachFeature,
            
                style: geo_json_1d21747c840786d83430ecb65cba9508_styler,
            ...{
}
        });

        function geo_json_1d21747c840786d83430ecb65cba9508_add (data) {
            geo_json_1d21747c840786d83430ecb65cba9508
                .addData(data);
        }
            geo_json_1d21747c840786d83430ecb65cba9508_add({"features": [{"geometry": {"coordinates": [[-79.25103, 43.880567], [-79.243745, 43.882287], [-79.244328, 43.884115], [-79.241514, 43.891636], [-79.24042, 43.893439], [-79.242867, 43.895348], [-79.246329, 43.894712], [-79.249146, 43.89317], [-79.253028, 43.892248], [-79.256783, 43.891363], [-79.258243, 43.891873], [-79.263777, 43.892147], [-79.268557, 43.89041], [-79.271529, 43.888084], [-79.268525, 43.888772], [-79.266779, 43.887351], [-79.266431, 43.885715], [-79.265999, 43.883238], [-79.268827, 43.880904], [-79.271019, 43.879651], [-79.274921, 43.879111], [-79.277784, 43.879335], [-79.281904, 43.877843], [-79.28577, 43.877275], [-79.289463, 43.876546], [-79.291537, 43.875804], [-79.2975, 43.874183], [-79.298981, 43.872615], [-79.300576, 43.871157], [-79.304738, 43.870237], [-79.309549, 43.869119], [-79.312073, 43.868926], [-79.313612, 43.869788], [-79.316283, 43.871618], [-79.318583, 43.872267], [-79.32192, 43.871533], [-79.323572, 43.871186], [-79.328023, 43.867853], [-79.326818, 43.865813], [-79.326193, 43.863634], [-79.329801, 43.86326], [-79.333283, 43.862332], [-79.333015, 43.860656], [-79.334075, 43.860161], [-79.33846, 43.86014], [-79.338482, 43.86158], [-79.339522, 43.864592], [-79.340041, 43.866439], [-79.34182, 43.867767], [-79.343789, 43.868159], [-79.347602, 43.867986], [-79.349411, 43.867433], [-79.352386, 43.86993], [-79.35487, 43.871832], [-79.355758, 43.872918], [-79.356843, 43.874324], [-79.358228, 43.876278], [-79.360937, 43.877293], [-79.364163, 43.876995]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_1d21747c840786d83430ecb65cba9508.bindTooltip(
                `<div>
                     410 MARKHAM DISTRICT SS VIA CARLTON
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_1d21747c840786d83430ecb65cba9508.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_9e8b9447b1c773fbe4f836b19450ddc7_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_9e8b9447b1c773fbe4f836b19450ddc7_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_9e8b9447b1c773fbe4f836b19450ddc7 = L.geoJson(null, {
                onEachFeature: geo_json_9e8b9447b1c773fbe4f836b19450ddc7_onEachFeature,
            
                style: geo_json_9e8b9447b1c773fbe4f836b19450ddc7_styler,
            ...{
}
        });

        function geo_json_9e8b9447b1c773fbe4f836b19450ddc7_add (data) {
            geo_json_9e8b9447b1c773fbe4f836b19450ddc7
                .addData(data);
        }
            geo_json_9e8b9447b1c773fbe4f836b19450ddc7_add({"features": [{"geometry": {"coordinates": [[-79.254995, 43.85625], [-79.251469, 43.856335], [-79.249599, 43.858584], [-79.247389, 43.858753], [-79.244804, 43.85819], [-79.243773, 43.856081], [-79.240725, 43.855013], [-79.237612, 43.855779], [-79.237012, 43.858498], [-79.231887, 43.85993], [-79.233443, 43.860308], [-79.234956, 43.861714], [-79.240301, 43.861221], [-79.241925, 43.86341], [-79.242542, 43.865355], [-79.24047, 43.865741], [-79.234929, 43.865519], [-79.2328, 43.86463], [-79.23145, 43.863808], [-79.229191, 43.864961], [-79.228804, 43.865879], [-79.227586, 43.86825], [-79.224816, 43.869773], [-79.221362, 43.870486], [-79.215883, 43.869552], [-79.212178, 43.868989], [-79.215984, 43.862601], [-79.221793, 43.860784], [-79.221587, 43.858225], [-79.224071, 43.860605], [-79.224746, 43.86225], [-79.227079, 43.864747], [-79.228887, 43.865279], [-79.230636, 43.865957], [-79.232671, 43.868936], [-79.23386, 43.875474], [-79.234601, 43.878512], [-79.235156, 43.880494], [-79.240721, 43.883096], [-79.243408, 43.882443], [-79.24801, 43.883446], [-79.250424, 43.882953], [-79.253971, 43.883109], [-79.255327, 43.882811], [-79.25103, 43.880567]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_9e8b9447b1c773fbe4f836b19450ddc7.bindTooltip(
                `<div>
                     411 MARKHAM DISTRICT SS VIA BOX GROVE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_9e8b9447b1c773fbe4f836b19450ddc7.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_f9569296ccfc916e344b1cbe7a1c9ce9_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_f9569296ccfc916e344b1cbe7a1c9ce9_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_f9569296ccfc916e344b1cbe7a1c9ce9 = L.geoJson(null, {
                onEachFeature: geo_json_f9569296ccfc916e344b1cbe7a1c9ce9_onEachFeature,
            
                style: geo_json_f9569296ccfc916e344b1cbe7a1c9ce9_styler,
            ...{
}
        });

        function geo_json_f9569296ccfc916e344b1cbe7a1c9ce9_add (data) {
            geo_json_f9569296ccfc916e344b1cbe7a1c9ce9
                .addData(data);
        }
            geo_json_f9569296ccfc916e344b1cbe7a1c9ce9_add({"features": [{"geometry": {"coordinates": [[-79.25103, 43.880567], [-79.243745, 43.882287], [-79.240992, 43.882924], [-79.235499, 43.880865], [-79.235086, 43.879252], [-79.234766, 43.878138], [-79.234261, 43.875921], [-79.232566, 43.868316], [-79.228804, 43.865879], [-79.227586, 43.86825], [-79.224816, 43.869773], [-79.221362, 43.870486], [-79.215883, 43.869552], [-79.212178, 43.868989], [-79.215984, 43.862601], [-79.221793, 43.860784], [-79.221587, 43.858225], [-79.224071, 43.860605], [-79.224746, 43.86225], [-79.227079, 43.864747], [-79.232257, 43.863842], [-79.232877, 43.864886], [-79.235645, 43.86577], [-79.240551, 43.865822], [-79.242494, 43.865525], [-79.242055, 43.863553], [-79.2401, 43.861056], [-79.235145, 43.861654], [-79.233822, 43.860387], [-79.232184, 43.859921], [-79.238215, 43.855653], [-79.240491, 43.855191], [-79.243854, 43.856569], [-79.244391, 43.857888], [-79.246777, 43.858916], [-79.249965, 43.858667], [-79.250189, 43.856946], [-79.25245, 43.85628], [-79.255417, 43.856361]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_f9569296ccfc916e344b1cbe7a1c9ce9.bindTooltip(
                `<div>
                     411 MARKHAM DISTRICT SS VIA BOX GROVE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_f9569296ccfc916e344b1cbe7a1c9ce9.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_93b12ce672985094b453732cc22794cc_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_93b12ce672985094b453732cc22794cc_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_93b12ce672985094b453732cc22794cc = L.geoJson(null, {
                onEachFeature: geo_json_93b12ce672985094b453732cc22794cc_onEachFeature,
            
                style: geo_json_93b12ce672985094b453732cc22794cc_styler,
            ...{
}
        });

        function geo_json_93b12ce672985094b453732cc22794cc_add (data) {
            geo_json_93b12ce672985094b453732cc22794cc
                .addData(data);
        }
            geo_json_93b12ce672985094b453732cc22794cc_add({"features": [{"geometry": {"coordinates": [[-79.402806, 43.828295], [-79.403553, 43.827828], [-79.402064, 43.821857], [-79.401553, 43.819937], [-79.399974, 43.818698], [-79.398076, 43.819085], [-79.392546, 43.820053], [-79.388203, 43.820321], [-79.384522, 43.819883], [-79.381479, 43.820266], [-79.379687, 43.820479], [-79.377729, 43.820718], [-79.372834, 43.82164], [-79.370339, 43.822161], [-79.367274, 43.819227], [-79.36857, 43.817466], [-79.367995, 43.815857], [-79.36581, 43.813176], [-79.362221, 43.813973], [-79.359907, 43.815483], [-79.360543, 43.817041], [-79.361261, 43.818737], [-79.362466, 43.821301], [-79.36554, 43.820788], [-79.366915, 43.819543]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_93b12ce672985094b453732cc22794cc.bindTooltip(
                `<div>
                     412 THORNLEA SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_93b12ce672985094b453732cc22794cc.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_6ea260f77decef842059a0b1da3eb151_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_6ea260f77decef842059a0b1da3eb151_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_6ea260f77decef842059a0b1da3eb151 = L.geoJson(null, {
                onEachFeature: geo_json_6ea260f77decef842059a0b1da3eb151_onEachFeature,
            
                style: geo_json_6ea260f77decef842059a0b1da3eb151_styler,
            ...{
}
        });

        function geo_json_6ea260f77decef842059a0b1da3eb151_add (data) {
            geo_json_6ea260f77decef842059a0b1da3eb151
                .addData(data);
        }
            geo_json_6ea260f77decef842059a0b1da3eb151_add({"features": [{"geometry": {"coordinates": [[-79.367274, 43.819227], [-79.36857, 43.817466], [-79.367995, 43.815857], [-79.36581, 43.813176], [-79.362221, 43.813973], [-79.359907, 43.815483], [-79.360543, 43.817041], [-79.361261, 43.818737], [-79.362466, 43.821301], [-79.36554, 43.820788], [-79.366915, 43.819543], [-79.372992, 43.821738], [-79.377696, 43.820836], [-79.379847, 43.820588], [-79.382036, 43.820329], [-79.384, 43.820105], [-79.387736, 43.820434], [-79.391877, 43.820376], [-79.397519, 43.819405], [-79.40051, 43.818836], [-79.401031, 43.818961], [-79.401617, 43.821607], [-79.403256, 43.827992], [-79.399457, 43.828655], [-79.398411, 43.829728], [-79.397656, 43.831061], [-79.394321, 43.831271], [-79.392946, 43.829956], [-79.39162, 43.828665], [-79.389816, 43.826813], [-79.388532, 43.823945], [-79.384864, 43.824733], [-79.380194, 43.82576], [-79.37823, 43.829448], [-79.376936, 43.830524], [-79.379357, 43.833513]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_6ea260f77decef842059a0b1da3eb151.bindTooltip(
                `<div>
                     413 ST ROBERT SS VIA JOHN
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_6ea260f77decef842059a0b1da3eb151.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_b46ff9eb5d5c1ab040ce172a90a96545_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_b46ff9eb5d5c1ab040ce172a90a96545_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_b46ff9eb5d5c1ab040ce172a90a96545 = L.geoJson(null, {
                onEachFeature: geo_json_b46ff9eb5d5c1ab040ce172a90a96545_onEachFeature,
            
                style: geo_json_b46ff9eb5d5c1ab040ce172a90a96545_styler,
            ...{
}
        });

        function geo_json_b46ff9eb5d5c1ab040ce172a90a96545_add (data) {
            geo_json_b46ff9eb5d5c1ab040ce172a90a96545
                .addData(data);
        }
            geo_json_b46ff9eb5d5c1ab040ce172a90a96545_add({"features": [{"geometry": {"coordinates": [[-79.379788, 43.833875], [-79.377226, 43.830443], [-79.379693, 43.825962], [-79.38452, 43.82491], [-79.389039, 43.823963], [-79.389807, 43.82708], [-79.391412, 43.828496], [-79.39269, 43.829901], [-79.394156, 43.831322], [-79.397527, 43.831267], [-79.398593, 43.830285], [-79.399409, 43.828782], [-79.402806, 43.828295], [-79.403553, 43.827828], [-79.402064, 43.821857], [-79.401553, 43.819937], [-79.399974, 43.818698], [-79.398076, 43.819085], [-79.392546, 43.820053], [-79.388203, 43.820321], [-79.384522, 43.819883], [-79.381479, 43.820266], [-79.379687, 43.820479], [-79.377729, 43.820718], [-79.372834, 43.82164], [-79.370339, 43.822161], [-79.367274, 43.819227], [-79.36857, 43.817466], [-79.367995, 43.815857], [-79.36581, 43.813176], [-79.362221, 43.813973], [-79.359907, 43.815483], [-79.360543, 43.817041], [-79.361261, 43.818737], [-79.362466, 43.821301], [-79.36554, 43.820788], [-79.366915, 43.819543]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_b46ff9eb5d5c1ab040ce172a90a96545.bindTooltip(
                `<div>
                     413 ST ROBERT SS VIA JOHN
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_b46ff9eb5d5c1ab040ce172a90a96545.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_baf80ba376865f6cdc8b988fda762148_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_baf80ba376865f6cdc8b988fda762148_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_baf80ba376865f6cdc8b988fda762148 = L.geoJson(null, {
                onEachFeature: geo_json_baf80ba376865f6cdc8b988fda762148_onEachFeature,
            
                style: geo_json_baf80ba376865f6cdc8b988fda762148_styler,
            ...{
}
        });

        function geo_json_baf80ba376865f6cdc8b988fda762148_add (data) {
            geo_json_baf80ba376865f6cdc8b988fda762148
                .addData(data);
        }
            geo_json_baf80ba376865f6cdc8b988fda762148_add({"features": [{"geometry": {"coordinates": [[-79.266333, 43.959696], [-79.258688, 43.961599], [-79.254891, 43.960077], [-79.251185, 43.955606], [-79.248781, 43.957105], [-79.245769, 43.958681], [-79.242335, 43.959183], [-79.241966, 43.960949], [-79.243212, 43.964791], [-79.240405, 43.966507], [-79.236421, 43.966607], [-79.234945, 43.966841], [-79.232186, 43.967423], [-79.229415, 43.968074], [-79.226988, 43.968553], [-79.224079, 43.969704], [-79.22101, 43.97063], [-79.224907, 43.976389], [-79.226863, 43.975919], [-79.230873, 43.974999], [-79.231851, 43.977926], [-79.23527, 43.979791], [-79.236816, 43.978632], [-79.240539, 43.978052], [-79.24365, 43.978059], [-79.248463, 43.977119], [-79.252585, 43.976618], [-79.256749, 43.97329], [-79.256311, 43.971165], [-79.260017, 43.968513], [-79.265058, 43.967462], [-79.27014, 43.966374], [-79.274293, 43.965375], [-79.275736, 43.96949], [-79.271618, 43.971009], [-79.26731, 43.972838], [-79.262574, 43.974287], [-79.259437, 43.974932], [-79.258512, 43.982443], [-79.254772, 43.98346]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_baf80ba376865f6cdc8b988fda762148.bindTooltip(
                `<div>
                     414 ST KATHARINE DREXEL SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_baf80ba376865f6cdc8b988fda762148.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_d2f194b9ce01e0a710bbab1430a4f977_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_d2f194b9ce01e0a710bbab1430a4f977_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_d2f194b9ce01e0a710bbab1430a4f977 = L.geoJson(null, {
                onEachFeature: geo_json_d2f194b9ce01e0a710bbab1430a4f977_onEachFeature,
            
                style: geo_json_d2f194b9ce01e0a710bbab1430a4f977_styler,
            ...{
}
        });

        function geo_json_d2f194b9ce01e0a710bbab1430a4f977_add (data) {
            geo_json_d2f194b9ce01e0a710bbab1430a4f977
                .addData(data);
        }
            geo_json_d2f194b9ce01e0a710bbab1430a4f977_add({"features": [{"geometry": {"coordinates": [[-79.254772, 43.98346], [-79.256749, 43.97329], [-79.256311, 43.971165], [-79.260017, 43.968513], [-79.265058, 43.967462], [-79.27014, 43.966374], [-79.274293, 43.965375], [-79.275736, 43.96949], [-79.271618, 43.971009], [-79.26731, 43.972838], [-79.262574, 43.974287], [-79.259437, 43.974932], [-79.257459, 43.975373], [-79.252785, 43.976439], [-79.248068, 43.977057], [-79.243331, 43.978005], [-79.240254, 43.97778], [-79.236626, 43.978564], [-79.23477, 43.979783], [-79.23273, 43.980222], [-79.232072, 43.978188], [-79.231416, 43.975378], [-79.227359, 43.975585], [-79.225119, 43.97616], [-79.220546, 43.971178], [-79.223907, 43.969982], [-79.227487, 43.968584], [-79.229756, 43.968101], [-79.234686, 43.967036], [-79.237164, 43.966887], [-79.24096, 43.966279], [-79.243354, 43.964823], [-79.242505, 43.961436], [-79.242115, 43.959595], [-79.244733, 43.958737], [-79.246308, 43.958786], [-79.248884, 43.957196], [-79.251481, 43.955652], [-79.253289, 43.955159], [-79.254311, 43.959129], [-79.259168, 43.961694], [-79.262449, 43.960802], [-79.265559, 43.96005]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_d2f194b9ce01e0a710bbab1430a4f977.bindTooltip(
                `<div>
                     414 ST KATHARINE DREXEL SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_d2f194b9ce01e0a710bbab1430a4f977.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_a7dd9dc7f5397c780918ccee16c326c2_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_a7dd9dc7f5397c780918ccee16c326c2_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_a7dd9dc7f5397c780918ccee16c326c2 = L.geoJson(null, {
                onEachFeature: geo_json_a7dd9dc7f5397c780918ccee16c326c2_onEachFeature,
            
                style: geo_json_a7dd9dc7f5397c780918ccee16c326c2_styler,
            ...{
}
        });

        function geo_json_a7dd9dc7f5397c780918ccee16c326c2_add (data) {
            geo_json_a7dd9dc7f5397c780918ccee16c326c2
                .addData(data);
        }
            geo_json_a7dd9dc7f5397c780918ccee16c326c2_add({"features": [{"geometry": {"coordinates": [[-79.280403, 43.969416], [-79.276455, 43.96972], [-79.271618, 43.971009], [-79.26731, 43.972838], [-79.262574, 43.974287], [-79.259437, 43.974932], [-79.257459, 43.975373], [-79.252785, 43.976439], [-79.248068, 43.977057], [-79.243331, 43.978005], [-79.240254, 43.97778], [-79.236626, 43.978564], [-79.23477, 43.979783], [-79.23273, 43.980222], [-79.232072, 43.978188], [-79.231416, 43.975378], [-79.227359, 43.975585], [-79.225119, 43.97616], [-79.220546, 43.971178], [-79.223907, 43.969982], [-79.227487, 43.968584], [-79.229756, 43.968101], [-79.234686, 43.967036], [-79.237164, 43.966887], [-79.24096, 43.966279], [-79.243354, 43.964823], [-79.242505, 43.961436], [-79.242115, 43.959595], [-79.244733, 43.958737], [-79.246308, 43.958786], [-79.248884, 43.957196], [-79.251481, 43.955652], [-79.253289, 43.955159], [-79.254311, 43.959129], [-79.259168, 43.961694]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_a7dd9dc7f5397c780918ccee16c326c2.bindTooltip(
                `<div>
                     415 STOUFFVILLE DISTRICT SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_a7dd9dc7f5397c780918ccee16c326c2.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_ac1e97597c0ba40be69aa7788cf99cc9_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_ac1e97597c0ba40be69aa7788cf99cc9_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_ac1e97597c0ba40be69aa7788cf99cc9 = L.geoJson(null, {
                onEachFeature: geo_json_ac1e97597c0ba40be69aa7788cf99cc9_onEachFeature,
            
                style: geo_json_ac1e97597c0ba40be69aa7788cf99cc9_styler,
            ...{
}
        });

        function geo_json_ac1e97597c0ba40be69aa7788cf99cc9_add (data) {
            geo_json_ac1e97597c0ba40be69aa7788cf99cc9
                .addData(data);
        }
            geo_json_ac1e97597c0ba40be69aa7788cf99cc9_add({"features": [{"geometry": {"coordinates": [[-79.258688, 43.961599], [-79.254891, 43.960077], [-79.251185, 43.955606], [-79.248781, 43.957105], [-79.245769, 43.958681], [-79.242335, 43.959183], [-79.241966, 43.960949], [-79.243212, 43.964791], [-79.240405, 43.966507], [-79.236421, 43.966607], [-79.234945, 43.966841], [-79.232186, 43.967423], [-79.229415, 43.968074], [-79.226988, 43.968553], [-79.224079, 43.969704], [-79.22101, 43.97063], [-79.224907, 43.976389], [-79.226863, 43.975919], [-79.230873, 43.974999], [-79.231851, 43.977926], [-79.23527, 43.979791], [-79.236816, 43.978632], [-79.240539, 43.978052], [-79.24365, 43.978059], [-79.248463, 43.977119], [-79.252585, 43.976618], [-79.256815, 43.975713], [-79.259495, 43.975087], [-79.263129, 43.97447], [-79.267602, 43.973048], [-79.271145, 43.971364], [-79.275406, 43.97021], [-79.279876, 43.969583]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_ac1e97597c0ba40be69aa7788cf99cc9.bindTooltip(
                `<div>
                     415 STOUFFVILLE DISTRICT SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_ac1e97597c0ba40be69aa7788cf99cc9.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_e4b5ded9ee6cea57770170f00fb0b3ae_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_e4b5ded9ee6cea57770170f00fb0b3ae_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_e4b5ded9ee6cea57770170f00fb0b3ae = L.geoJson(null, {
                onEachFeature: geo_json_e4b5ded9ee6cea57770170f00fb0b3ae_onEachFeature,
            
                style: geo_json_e4b5ded9ee6cea57770170f00fb0b3ae_styler,
            ...{
}
        });

        function geo_json_e4b5ded9ee6cea57770170f00fb0b3ae_add (data) {
            geo_json_e4b5ded9ee6cea57770170f00fb0b3ae
                .addData(data);
        }
            geo_json_e4b5ded9ee6cea57770170f00fb0b3ae_add({"features": [{"geometry": {"coordinates": [[-79.227586, 43.86825], [-79.224816, 43.869773], [-79.221362, 43.870486], [-79.215883, 43.869552], [-79.212178, 43.868989], [-79.215984, 43.862601], [-79.217444, 43.860445], [-79.21979, 43.857719], [-79.222375, 43.857421], [-79.225124, 43.856733], [-79.228948, 43.855739], [-79.229979, 43.85942], [-79.224746, 43.86225], [-79.227079, 43.864747], [-79.228887, 43.865279], [-79.230636, 43.865957], [-79.232671, 43.868936], [-79.23386, 43.875474], [-79.231531, 43.875932], [-79.22746, 43.876717], [-79.228648, 43.878956], [-79.225589, 43.880425], [-79.227727, 43.884372], [-79.230203, 43.885522], [-79.233171, 43.884872], [-79.234428, 43.884572], [-79.240721, 43.883096], [-79.243408, 43.882443], [-79.24801, 43.883446], [-79.250424, 43.882953], [-79.253971, 43.883109], [-79.255327, 43.882811], [-79.25103, 43.880567]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_e4b5ded9ee6cea57770170f00fb0b3ae.bindTooltip(
                `<div>
                     416 MARKHAM DISTRICT SS VIA NINTH LINE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_e4b5ded9ee6cea57770170f00fb0b3ae.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_c513d87595c0faaec379afa26e100e62_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_c513d87595c0faaec379afa26e100e62_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_c513d87595c0faaec379afa26e100e62 = L.geoJson(null, {
                onEachFeature: geo_json_c513d87595c0faaec379afa26e100e62_onEachFeature,
            
                style: geo_json_c513d87595c0faaec379afa26e100e62_styler,
            ...{
}
        });

        function geo_json_c513d87595c0faaec379afa26e100e62_add (data) {
            geo_json_c513d87595c0faaec379afa26e100e62
                .addData(data);
        }
            geo_json_c513d87595c0faaec379afa26e100e62_add({"features": [{"geometry": {"coordinates": [[-79.25103, 43.880567], [-79.243745, 43.882287], [-79.240992, 43.882924], [-79.235234, 43.884241], [-79.23433, 43.884453], [-79.232901, 43.884803], [-79.229955, 43.885504], [-79.229063, 43.884952], [-79.226104, 43.881117], [-79.227385, 43.876962], [-79.231658, 43.87603], [-79.232566, 43.868316], [-79.228804, 43.865879], [-79.227586, 43.86825], [-79.224816, 43.869773], [-79.221362, 43.870486], [-79.215883, 43.869552], [-79.212178, 43.868989], [-79.215984, 43.862601], [-79.217444, 43.860445], [-79.21979, 43.857719], [-79.222375, 43.857421], [-79.225124, 43.856733], [-79.228948, 43.855739], [-79.229979, 43.85942], [-79.224746, 43.86225], [-79.227079, 43.864747]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_c513d87595c0faaec379afa26e100e62.bindTooltip(
                `<div>
                     416 MARKHAM DISTRICT SS VIA NINTH LINE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_c513d87595c0faaec379afa26e100e62.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_36b66d1b0ae358ab04f087fdfc0d60a3_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#636569", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_36b66d1b0ae358ab04f087fdfc0d60a3_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_36b66d1b0ae358ab04f087fdfc0d60a3 = L.geoJson(null, {
                onEachFeature: geo_json_36b66d1b0ae358ab04f087fdfc0d60a3_onEachFeature,
            
                style: geo_json_36b66d1b0ae358ab04f087fdfc0d60a3_styler,
            ...{
}
        });

        function geo_json_36b66d1b0ae358ab04f087fdfc0d60a3_add (data) {
            geo_json_36b66d1b0ae358ab04f087fdfc0d60a3
                .addData(data);
        }
            geo_json_36b66d1b0ae358ab04f087fdfc0d60a3_add({"features": [{"geometry": {"coordinates": [[-79.266333, 43.959696], [-79.258688, 43.961599], [-79.254891, 43.960077], [-79.251185, 43.955606], [-79.248781, 43.957105], [-79.245769, 43.958681], [-79.242335, 43.959183], [-79.241966, 43.960949], [-79.243212, 43.964791], [-79.240405, 43.966507], [-79.236421, 43.966607], [-79.234945, 43.966841], [-79.232186, 43.967423], [-79.230514, 43.968598], [-79.231079, 43.97095], [-79.232892, 43.974523], [-79.238029, 43.973404], [-79.243459, 43.972184], [-79.246891, 43.971391], [-79.249993, 43.970707], [-79.25405, 43.969808], [-79.256705, 43.969241], [-79.260017, 43.968513], [-79.265058, 43.967462], [-79.27014, 43.966374], [-79.274293, 43.965375], [-79.275736, 43.96949], [-79.271618, 43.971009], [-79.26731, 43.972838], [-79.262574, 43.974287], [-79.259437, 43.974932], [-79.257459, 43.975373], [-79.252785, 43.976439], [-79.248068, 43.977057], [-79.243331, 43.978005], [-79.240254, 43.97778], [-79.238453, 43.973448], [-79.243459, 43.972184], [-79.246891, 43.971391], [-79.249993, 43.970707], [-79.25405, 43.969808], [-79.256552, 43.967389], [-79.255956, 43.964805], [-79.255462, 43.9625], [-79.254891, 43.960077], [-79.25373, 43.955255], [-79.249904, 43.939081], [-79.248753, 43.933546], [-79.246719, 43.925651], [-79.245332, 43.919986], [-79.244356, 43.91596], [-79.241082, 43.905538], [-79.240829, 43.902566], [-79.2404, 43.900311], [-79.239793, 43.897885], [-79.238995, 43.894803], [-79.238255, 43.891857], [-79.237438, 43.888719], [-79.237123, 43.887206], [-79.235234, 43.884241], [-79.23433, 43.884453], [-79.232901, 43.884803], [-79.229955, 43.885504], [-79.229499, 43.886931], [-79.229819, 43.888092], [-79.230233, 43.889539], [-79.23086, 43.892056]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_36b66d1b0ae358ab04f087fdfc0d60a3.bindTooltip(
                `<div>
                     417 BILL HOGARTH SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_36b66d1b0ae358ab04f087fdfc0d60a3.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_ee8337cfc3d8de10e3c73014c3c7439e_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#636569", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_ee8337cfc3d8de10e3c73014c3c7439e_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_ee8337cfc3d8de10e3c73014c3c7439e = L.geoJson(null, {
                onEachFeature: geo_json_ee8337cfc3d8de10e3c73014c3c7439e_onEachFeature,
            
                style: geo_json_ee8337cfc3d8de10e3c73014c3c7439e_styler,
            ...{
}
        });

        function geo_json_ee8337cfc3d8de10e3c73014c3c7439e_add (data) {
            geo_json_ee8337cfc3d8de10e3c73014c3c7439e
                .addData(data);
        }
            geo_json_ee8337cfc3d8de10e3c73014c3c7439e_add({"features": [{"geometry": {"coordinates": [[-79.23086, 43.892056], [-79.23142, 43.894171], [-79.232934, 43.895689], [-79.235427, 43.895352], [-79.238311, 43.894682], [-79.239368, 43.897522], [-79.239967, 43.899888], [-79.240465, 43.902051], [-79.240643, 43.904857], [-79.243825, 43.91529], [-79.244991, 43.919984], [-79.246432, 43.925673], [-79.248152, 43.932974], [-79.249689, 43.939015], [-79.252392, 43.950602], [-79.253383, 43.95487], [-79.251185, 43.955606], [-79.248781, 43.957105], [-79.245769, 43.958681], [-79.242335, 43.959183], [-79.241966, 43.960949], [-79.243212, 43.964791], [-79.240405, 43.966507], [-79.236421, 43.966607], [-79.234945, 43.966841], [-79.232186, 43.967423], [-79.230514, 43.968598], [-79.231079, 43.97095], [-79.232892, 43.974523], [-79.238029, 43.973404], [-79.243459, 43.972184], [-79.246891, 43.971391], [-79.249993, 43.970707], [-79.25405, 43.969808], [-79.256705, 43.969241], [-79.260017, 43.968513], [-79.265058, 43.967462], [-79.27014, 43.966374], [-79.274293, 43.965375], [-79.275736, 43.96949], [-79.271618, 43.971009], [-79.26731, 43.972838], [-79.262574, 43.974287], [-79.259437, 43.974932], [-79.257459, 43.975373], [-79.252785, 43.976439], [-79.248068, 43.977057], [-79.243331, 43.978005], [-79.240254, 43.97778], [-79.238453, 43.973448], [-79.243459, 43.972184], [-79.246891, 43.971391], [-79.249993, 43.970707], [-79.25405, 43.969808], [-79.256552, 43.967389], [-79.255956, 43.964805], [-79.255462, 43.9625], [-79.259168, 43.961694], [-79.262449, 43.960802], [-79.265559, 43.96005]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_ee8337cfc3d8de10e3c73014c3c7439e.bindTooltip(
                `<div>
                     417 BILL HOGARTH SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_ee8337cfc3d8de10e3c73014c3c7439e.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_165196a64e3e7b1fe9966933ab66c255_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_165196a64e3e7b1fe9966933ab66c255_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_165196a64e3e7b1fe9966933ab66c255 = L.geoJson(null, {
                onEachFeature: geo_json_165196a64e3e7b1fe9966933ab66c255_onEachFeature,
            
                style: geo_json_165196a64e3e7b1fe9966933ab66c255_styler,
            ...{
}
        });

        function geo_json_165196a64e3e7b1fe9966933ab66c255_add (data) {
            geo_json_165196a64e3e7b1fe9966933ab66c255
                .addData(data);
        }
            geo_json_165196a64e3e7b1fe9966933ab66c255_add({"features": [{"geometry": {"coordinates": [[-79.371269, 43.896769], [-79.372906, 43.896763], [-79.376758, 43.896583], [-79.378487, 43.896996], [-79.377247, 43.899746], [-79.377272, 43.901278], [-79.375154, 43.903251], [-79.372092, 43.903953], [-79.37074, 43.899619], [-79.367871, 43.896972], [-79.366251, 43.894185], [-79.36526, 43.89187], [-79.362932, 43.889548], [-79.361844, 43.887451], [-79.366976, 43.884408], [-79.366257, 43.881318], [-79.364004, 43.876817], [-79.362234, 43.87708], [-79.360496, 43.877173], [-79.358776, 43.876642], [-79.357482, 43.874949], [-79.356229, 43.873223], [-79.355096, 43.871826], [-79.348308, 43.870963], [-79.343303, 43.872084], [-79.339006, 43.873763], [-79.332325, 43.875314], [-79.32702, 43.876502], [-79.321988, 43.877689], [-79.317446, 43.878739], [-79.314435, 43.881422], [-79.31543, 43.884984], [-79.316355, 43.888251], [-79.315666, 43.888557], [-79.312012, 43.889341]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_165196a64e3e7b1fe9966933ab66c255.bindTooltip(
                `<div>
                     418 PIERRE ELLIOTT TRUDEAU SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_165196a64e3e7b1fe9966933ab66c255.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_1f62bba26b617ceb424cba2ed5e7a07d_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_1f62bba26b617ceb424cba2ed5e7a07d_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_1f62bba26b617ceb424cba2ed5e7a07d = L.geoJson(null, {
                onEachFeature: geo_json_1f62bba26b617ceb424cba2ed5e7a07d_onEachFeature,
            
                style: geo_json_1f62bba26b617ceb424cba2ed5e7a07d_styler,
            ...{
}
        });

        function geo_json_1f62bba26b617ceb424cba2ed5e7a07d_add (data) {
            geo_json_1f62bba26b617ceb424cba2ed5e7a07d
                .addData(data);
        }
            geo_json_1f62bba26b617ceb424cba2ed5e7a07d_add({"features": [{"geometry": {"coordinates": [[-79.313366, 43.889234], [-79.315923, 43.885384], [-79.31512, 43.882335], [-79.314525, 43.879725], [-79.31704, 43.879032], [-79.321309, 43.878027], [-79.326604, 43.876847], [-79.331888, 43.875608], [-79.338317, 43.874148], [-79.342901, 43.87241], [-79.347823, 43.871292], [-79.352193, 43.870281], [-79.35487, 43.871832], [-79.355758, 43.872918], [-79.356843, 43.874324], [-79.358228, 43.876278], [-79.360937, 43.877293], [-79.364163, 43.876995], [-79.365843, 43.880997], [-79.366999, 43.885748], [-79.367353, 43.887033], [-79.368629, 43.888654], [-79.368384, 43.89068], [-79.368918, 43.89311], [-79.371269, 43.896769], [-79.372906, 43.896763], [-79.376758, 43.896583], [-79.378487, 43.896996], [-79.377247, 43.899746], [-79.377272, 43.901278], [-79.375154, 43.903251], [-79.372092, 43.903953], [-79.37074, 43.899619], [-79.367871, 43.896972], [-79.366251, 43.894185], [-79.36526, 43.89187], [-79.362932, 43.889548], [-79.361844, 43.887451]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_1f62bba26b617ceb424cba2ed5e7a07d.bindTooltip(
                `<div>
                     418 PIERRE ELLIOTT TRUDEAU SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_1f62bba26b617ceb424cba2ed5e7a07d.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_f677cd2a051c0b609b1b8c4a50ed67d2_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_f677cd2a051c0b609b1b8c4a50ed67d2_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_f677cd2a051c0b609b1b8c4a50ed67d2 = L.geoJson(null, {
                onEachFeature: geo_json_f677cd2a051c0b609b1b8c4a50ed67d2_onEachFeature,
            
                style: geo_json_f677cd2a051c0b609b1b8c4a50ed67d2_styler,
            ...{
}
        });

        function geo_json_f677cd2a051c0b609b1b8c4a50ed67d2_add (data) {
            geo_json_f677cd2a051c0b609b1b8c4a50ed67d2
                .addData(data);
        }
            geo_json_f677cd2a051c0b609b1b8c4a50ed67d2_add({"features": [{"geometry": {"coordinates": [[-79.486929, 44.053065], [-79.490529, 44.052823], [-79.494287, 44.049601], [-79.491923, 44.048508], [-79.490572, 44.046084], [-79.492695, 44.044809], [-79.498982, 44.044686], [-79.502032, 44.045717], [-79.504314, 44.045597], [-79.501475, 44.038827], [-79.497084, 44.035591], [-79.49471, 44.036146], [-79.491142, 44.036703], [-79.487338, 44.037712], [-79.485033, 44.038568], [-79.483367, 44.036498], [-79.481753, 44.034889], [-79.476288, 44.036089], [-79.474977, 44.036404], [-79.469275, 44.037693], [-79.468445, 44.03574], [-79.470007, 44.033681], [-79.473681, 44.032236], [-79.472736, 44.029267], [-79.47229, 44.027235], [-79.470546, 44.026469], [-79.466882, 44.027608], [-79.468006, 44.030041], [-79.469801, 44.033556], [-79.46834, 44.035696], [-79.468965, 44.037692], [-79.464527, 44.038766], [-79.458145, 44.040187], [-79.454931, 44.040843], [-79.452288, 44.041066], [-79.449653, 44.041436], [-79.446665, 44.042756], [-79.435186, 44.047194]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_f677cd2a051c0b609b1b8c4a50ed67d2.bindTooltip(
                `<div>
                     420 NEWMARKET SS VIA SAVAGE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_f677cd2a051c0b609b1b8c4a50ed67d2.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_76960d3c7505a0e681726cffc6621617_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_76960d3c7505a0e681726cffc6621617_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_76960d3c7505a0e681726cffc6621617 = L.geoJson(null, {
                onEachFeature: geo_json_76960d3c7505a0e681726cffc6621617_onEachFeature,
            
                style: geo_json_76960d3c7505a0e681726cffc6621617_styler,
            ...{
}
        });

        function geo_json_76960d3c7505a0e681726cffc6621617_add (data) {
            geo_json_76960d3c7505a0e681726cffc6621617
                .addData(data);
        }
            geo_json_76960d3c7505a0e681726cffc6621617_add({"features": [{"geometry": {"coordinates": [[-79.434646, 44.04598], [-79.437716, 44.045312], [-79.446418, 44.043226], [-79.451657, 44.041408], [-79.454534, 44.041183], [-79.458408, 44.040335], [-79.463762, 44.039164], [-79.468445, 44.03574], [-79.470007, 44.033681], [-79.473681, 44.032236], [-79.472736, 44.029267], [-79.47229, 44.027235], [-79.470546, 44.026469], [-79.466882, 44.027608], [-79.468006, 44.030041], [-79.469801, 44.033556], [-79.46834, 44.035696], [-79.468965, 44.037692], [-79.475563, 44.036497], [-79.482342, 44.035022], [-79.483159, 44.036269], [-79.484794, 44.038615], [-79.487725, 44.037613], [-79.490749, 44.036781], [-79.494481, 44.036283], [-79.497105, 44.035776], [-79.500745, 44.038542], [-79.505057, 44.045108], [-79.502285, 44.045768], [-79.499299, 44.044684], [-79.4929, 44.044649], [-79.490103, 44.04614], [-79.491564, 44.04858], [-79.493972, 44.049537], [-79.49602, 44.050623], [-79.491139, 44.052399], [-79.486929, 44.053065]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_76960d3c7505a0e681726cffc6621617.bindTooltip(
                `<div>
                     420 NEWMARKET SS VIA SAVAGE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_76960d3c7505a0e681726cffc6621617.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_ba88716a611ca1ec966a6d4433049306_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_ba88716a611ca1ec966a6d4433049306_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_ba88716a611ca1ec966a6d4433049306 = L.geoJson(null, {
                onEachFeature: geo_json_ba88716a611ca1ec966a6d4433049306_onEachFeature,
            
                style: geo_json_ba88716a611ca1ec966a6d4433049306_styler,
            ...{
}
        });

        function geo_json_ba88716a611ca1ec966a6d4433049306_add (data) {
            geo_json_ba88716a611ca1ec966a6d4433049306
                .addData(data);
        }
            geo_json_ba88716a611ca1ec966a6d4433049306_add({"features": [{"geometry": {"coordinates": [[-79.434646, 44.04598], [-79.437716, 44.045312], [-79.446418, 44.043226], [-79.451657, 44.041408], [-79.454534, 44.041183], [-79.458408, 44.040335], [-79.463762, 44.039164], [-79.468974, 44.038027], [-79.468844, 44.040113], [-79.469965, 44.042635], [-79.471041, 44.045666], [-79.469916, 44.047199], [-79.467211, 44.047803], [-79.462951, 44.049338], [-79.464121, 44.052232], [-79.465124, 44.054652], [-79.465986, 44.057612], [-79.47188, 44.056898], [-79.471872, 44.057863], [-79.473436, 44.060384], [-79.475011, 44.062534], [-79.475573, 44.06383], [-79.47344, 44.064379], [-79.471127, 44.065142], [-79.468969, 44.067164], [-79.469509, 44.069019], [-79.470832, 44.069752], [-79.474723, 44.06931], [-79.477432, 44.068301], [-79.482334, 44.068282], [-79.484666, 44.067863], [-79.48887, 44.067174], [-79.493402, 44.065866], [-79.492756, 44.063214], [-79.492302, 44.059879], [-79.493416, 44.058609], [-79.496079, 44.056725], [-79.499746, 44.056254], [-79.503831, 44.056004], [-79.505347, 44.05537]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_ba88716a611ca1ec966a6d4433049306.bindTooltip(
                `<div>
                     423 NEWMARKET SS VIA BRISTOL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_ba88716a611ca1ec966a6d4433049306.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_5a8428855a0e5daf89d2fe83a4e2fdc5_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_5a8428855a0e5daf89d2fe83a4e2fdc5_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_5a8428855a0e5daf89d2fe83a4e2fdc5 = L.geoJson(null, {
                onEachFeature: geo_json_5a8428855a0e5daf89d2fe83a4e2fdc5_onEachFeature,
            
                style: geo_json_5a8428855a0e5daf89d2fe83a4e2fdc5_styler,
            ...{
}
        });

        function geo_json_5a8428855a0e5daf89d2fe83a4e2fdc5_add (data) {
            geo_json_5a8428855a0e5daf89d2fe83a4e2fdc5
                .addData(data);
        }
            geo_json_5a8428855a0e5daf89d2fe83a4e2fdc5_add({"features": [{"geometry": {"coordinates": [[-79.505506, 44.055128], [-79.503415, 44.055955], [-79.499455, 44.056179], [-79.495708, 44.056696], [-79.493721, 44.058153], [-79.492169, 44.059548], [-79.492496, 44.062926], [-79.493228, 44.065905], [-79.488666, 44.067101], [-79.482029, 44.068211], [-79.477738, 44.068247], [-79.474999, 44.069128], [-79.47113, 44.069557], [-79.468888, 44.067387], [-79.470899, 44.065514], [-79.473182, 44.064527], [-79.475497, 44.064005], [-79.473702, 44.060804], [-79.471943, 44.057943], [-79.468047, 44.057485], [-79.466081, 44.057374], [-79.465411, 44.055042], [-79.464412, 44.052584], [-79.462995, 44.049048], [-79.467013, 44.047952], [-79.46923, 44.047462], [-79.471217, 44.045756], [-79.470084, 44.042636], [-79.46898, 44.040314], [-79.469304, 44.037995], [-79.464527, 44.038766], [-79.458145, 44.040187], [-79.454931, 44.040843], [-79.452288, 44.041066], [-79.449653, 44.041436], [-79.446665, 44.042756], [-79.435186, 44.047194]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_5a8428855a0e5daf89d2fe83a4e2fdc5.bindTooltip(
                `<div>
                     423 NEWMARKET SS VIA BRISTOL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_5a8428855a0e5daf89d2fe83a4e2fdc5.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_18130c11b569e3d505f2976d12b21591_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_18130c11b569e3d505f2976d12b21591_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_18130c11b569e3d505f2976d12b21591 = L.geoJson(null, {
                onEachFeature: geo_json_18130c11b569e3d505f2976d12b21591_onEachFeature,
            
                style: geo_json_18130c11b569e3d505f2976d12b21591_styler,
            ...{
}
        });

        function geo_json_18130c11b569e3d505f2976d12b21591_add (data) {
            geo_json_18130c11b569e3d505f2976d12b21591
                .addData(data);
        }
            geo_json_18130c11b569e3d505f2976d12b21591_add({"features": [{"geometry": {"coordinates": [[-79.462805, 44.19944], [-79.459601, 44.199596], [-79.458649, 44.197414], [-79.457637, 44.194985], [-79.460238, 44.194318], [-79.464175, 44.193456], [-79.467242, 44.192727], [-79.472201, 44.191636], [-79.476278, 44.190741], [-79.479074, 44.19112], [-79.480174, 44.195623], [-79.478255, 44.19975], [-79.470009, 44.20157], [-79.467043, 44.201804], [-79.467198, 44.205099], [-79.466741, 44.20866], [-79.464901, 44.21207], [-79.464542, 44.214682], [-79.464309, 44.216522], [-79.465149, 44.219126], [-79.465328, 44.223358], [-79.462592, 44.223566], [-79.459018, 44.222849], [-79.453659, 44.222855], [-79.451599, 44.223328], [-79.447067, 44.225064], [-79.447279, 44.228758], [-79.448077, 44.232006], [-79.448582, 44.234018], [-79.449232, 44.236411], [-79.451398, 44.24036], [-79.455008, 44.240077], [-79.457011, 44.243205], [-79.461566, 44.243696], [-79.460841, 44.240686], [-79.463601, 44.238479], [-79.465666, 44.240644], [-79.468331, 44.241708], [-79.470541, 44.242708], [-79.472934, 44.242209], [-79.474317, 44.241507], [-79.470912, 44.237937], [-79.467643, 44.235232], [-79.465785, 44.232903], [-79.465366, 44.229109], [-79.454328, 44.222799], [-79.458958, 44.222917]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_18130c11b569e3d505f2976d12b21591.bindTooltip(
                `<div>
                     424 KESWICK SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_18130c11b569e3d505f2976d12b21591.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_a681cfe038e5a52d433cdeddfe7c1125_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_a681cfe038e5a52d433cdeddfe7c1125_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_a681cfe038e5a52d433cdeddfe7c1125 = L.geoJson(null, {
                onEachFeature: geo_json_a681cfe038e5a52d433cdeddfe7c1125_onEachFeature,
            
                style: geo_json_a681cfe038e5a52d433cdeddfe7c1125_styler,
            ...{
}
        });

        function geo_json_a681cfe038e5a52d433cdeddfe7c1125_add (data) {
            geo_json_a681cfe038e5a52d433cdeddfe7c1125
                .addData(data);
        }
            geo_json_a681cfe038e5a52d433cdeddfe7c1125_add({"features": [{"geometry": {"coordinates": [[-79.459018, 44.222849], [-79.453659, 44.222855], [-79.451599, 44.223328], [-79.447067, 44.225064], [-79.447279, 44.228758], [-79.448077, 44.232006], [-79.448582, 44.234018], [-79.449232, 44.236411], [-79.451398, 44.24036], [-79.455008, 44.240077], [-79.457011, 44.243205], [-79.461566, 44.243696], [-79.460841, 44.240686], [-79.463601, 44.238479], [-79.465666, 44.240644], [-79.468331, 44.241708], [-79.470541, 44.242708], [-79.472934, 44.242209], [-79.474317, 44.241507], [-79.470912, 44.237937], [-79.467643, 44.235232], [-79.465785, 44.232903], [-79.465366, 44.229109], [-79.454328, 44.222799], [-79.458958, 44.222917], [-79.46223, 44.22367], [-79.465733, 44.223007], [-79.465247, 44.218881], [-79.464543, 44.216168], [-79.46661, 44.209188], [-79.467495, 44.205378], [-79.466514, 44.201387], [-79.466076, 44.199701], [-79.462805, 44.19944], [-79.459601, 44.199596], [-79.458649, 44.197414], [-79.457637, 44.194985], [-79.460238, 44.194318], [-79.464175, 44.193456], [-79.467242, 44.192727], [-79.472201, 44.191636], [-79.476278, 44.190741], [-79.479074, 44.19112], [-79.480174, 44.195623], [-79.478255, 44.19975], [-79.470009, 44.20157], [-79.467043, 44.201804]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_a681cfe038e5a52d433cdeddfe7c1125.bindTooltip(
                `<div>
                     424 KESWICK SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_a681cfe038e5a52d433cdeddfe7c1125.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_5930939def41d91ca468b2b0aae6e0f1_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_5930939def41d91ca468b2b0aae6e0f1_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_5930939def41d91ca468b2b0aae6e0f1 = L.geoJson(null, {
                onEachFeature: geo_json_5930939def41d91ca468b2b0aae6e0f1_onEachFeature,
            
                style: geo_json_5930939def41d91ca468b2b0aae6e0f1_styler,
            ...{
}
        });

        function geo_json_5930939def41d91ca468b2b0aae6e0f1_add (data) {
            geo_json_5930939def41d91ca468b2b0aae6e0f1
                .addData(data);
        }
            geo_json_5930939def41d91ca468b2b0aae6e0f1_add({"features": [{"geometry": {"coordinates": [[-79.489949, 44.095346], [-79.490539, 44.097626], [-79.491401, 44.101178], [-79.492225, 44.104226], [-79.492458, 44.10541], [-79.492094, 44.109966], [-79.492816, 44.113506], [-79.49365, 44.116918], [-79.494544, 44.120328], [-79.495662, 44.125342], [-79.49629, 44.12799], [-79.498267, 44.12792], [-79.506972, 44.126059], [-79.508734, 44.125152], [-79.511199, 44.120446], [-79.510109, 44.116463], [-79.508328, 44.109775], [-79.50758, 44.106861], [-79.505528, 44.10649], [-79.504658, 44.103292], [-79.497508, 44.100307], [-79.491829, 44.101339], [-79.490753, 44.097778], [-79.486483, 44.095834], [-79.482223, 44.096726], [-79.47798, 44.097649], [-79.476882, 44.095523], [-79.475067, 44.095205], [-79.473244, 44.094834], [-79.473684, 44.097323], [-79.466429, 44.100234], [-79.441455, 44.102526], [-79.440615, 44.099566], [-79.439953, 44.097201], [-79.438819, 44.092674], [-79.436818, 44.084337], [-79.43743, 44.084112], [-79.459318, 44.073858], [-79.45909, 44.070083], [-79.459931, 44.068101], [-79.462935, 44.064472], [-79.462556, 44.062077], [-79.458961, 44.059392], [-79.455828, 44.060245], [-79.454515, 44.06049], [-79.452712, 44.060904], [-79.449566, 44.061604], [-79.445043, 44.063472]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_5930939def41d91ca468b2b0aae6e0f1.bindTooltip(
                `<div>
                     425 HURON HEIGHTS SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_5930939def41d91ca468b2b0aae6e0f1.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_b8c5a4016adc495356a06c50bc83587a_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_b8c5a4016adc495356a06c50bc83587a_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_b8c5a4016adc495356a06c50bc83587a = L.geoJson(null, {
                onEachFeature: geo_json_b8c5a4016adc495356a06c50bc83587a_onEachFeature,
            
                style: geo_json_b8c5a4016adc495356a06c50bc83587a_styler,
            ...{
}
        });

        function geo_json_b8c5a4016adc495356a06c50bc83587a_add (data) {
            geo_json_b8c5a4016adc495356a06c50bc83587a
                .addData(data);
        }
            geo_json_b8c5a4016adc495356a06c50bc83587a_add({"features": [{"geometry": {"coordinates": [[-79.445046, 44.063053], [-79.449215, 44.061995], [-79.45184, 44.061384], [-79.454082, 44.060876], [-79.456139, 44.060444], [-79.459338, 44.05966], [-79.462242, 44.061675], [-79.463102, 44.063907], [-79.459733, 44.067652], [-79.459095, 44.0698], [-79.459121, 44.073605], [-79.43862, 44.092573], [-79.439664, 44.096663], [-79.44043, 44.099704], [-79.441029, 44.102008], [-79.446499, 44.10504], [-79.474087, 44.098303], [-79.47328, 44.094406], [-79.474845, 44.095147], [-79.476596, 44.095509], [-79.47748, 44.097214], [-79.481909, 44.096944], [-79.485332, 44.096184], [-79.48926, 44.095648], [-79.490539, 44.097626], [-79.491401, 44.101178], [-79.492225, 44.104226], [-79.492458, 44.10541], [-79.492094, 44.109966], [-79.492816, 44.113506], [-79.49365, 44.116918], [-79.494544, 44.120328], [-79.495662, 44.125342], [-79.49629, 44.12799], [-79.498267, 44.12792], [-79.506972, 44.126059], [-79.508734, 44.125152], [-79.511199, 44.120446], [-79.510109, 44.116463], [-79.508328, 44.109775], [-79.50758, 44.106861], [-79.505528, 44.10649], [-79.504658, 44.103292], [-79.497508, 44.100307], [-79.491829, 44.101339]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_b8c5a4016adc495356a06c50bc83587a.bindTooltip(
                `<div>
                     425 HURON HEIGHTS SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_b8c5a4016adc495356a06c50bc83587a.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_db4443fa879c1c999e23abb8e533dbbc_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_db4443fa879c1c999e23abb8e533dbbc_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_db4443fa879c1c999e23abb8e533dbbc = L.geoJson(null, {
                onEachFeature: geo_json_db4443fa879c1c999e23abb8e533dbbc_onEachFeature,
            
                style: geo_json_db4443fa879c1c999e23abb8e533dbbc_styler,
            ...{
}
        });

        function geo_json_db4443fa879c1c999e23abb8e533dbbc_add (data) {
            geo_json_db4443fa879c1c999e23abb8e533dbbc
                .addData(data);
        }
            geo_json_db4443fa879c1c999e23abb8e533dbbc_add({"features": [{"geometry": {"coordinates": [[-79.445908, 44.012601], [-79.442315, 44.013226], [-79.442864, 44.014563], [-79.443418, 44.016091], [-79.444529, 44.019378], [-79.446567, 44.019296], [-79.448821, 44.019023], [-79.451846, 44.018652], [-79.455019, 44.017014], [-79.453243, 44.016353], [-79.451009, 44.016442], [-79.450156, 44.014795], [-79.45309, 44.013818], [-79.454578, 44.012761], [-79.454141, 44.011242], [-79.451327, 44.01136], [-79.450634, 44.010099], [-79.450093, 44.008411], [-79.449775, 44.007526], [-79.4508, 44.005608], [-79.451138, 44.003543], [-79.452112, 44.003147], [-79.454002, 44.002749], [-79.457317, 44.002018], [-79.461642, 43.99122]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_db4443fa879c1c999e23abb8e533dbbc.bindTooltip(
                `<div>
                     426 DR G.W. WILLIAMS SS VIA HOLLIDGE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_db4443fa879c1c999e23abb8e533dbbc.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_b84f190ef43d4eedd120ec2120af8580_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_b84f190ef43d4eedd120ec2120af8580_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_b84f190ef43d4eedd120ec2120af8580 = L.geoJson(null, {
                onEachFeature: geo_json_b84f190ef43d4eedd120ec2120af8580_onEachFeature,
            
                style: geo_json_b84f190ef43d4eedd120ec2120af8580_styler,
            ...{
}
        });

        function geo_json_b84f190ef43d4eedd120ec2120af8580_add (data) {
            geo_json_b84f190ef43d4eedd120ec2120af8580
                .addData(data);
        }
            geo_json_b84f190ef43d4eedd120ec2120af8580_add({"features": [{"geometry": {"coordinates": [[-79.463224, 43.990875], [-79.456992, 44.001909], [-79.45109, 44.003907], [-79.45028, 44.006021], [-79.449795, 44.008027], [-79.450217, 44.009352], [-79.450828, 44.011154], [-79.447163, 44.012308], [-79.445908, 44.012601], [-79.442315, 44.013226], [-79.442864, 44.014563], [-79.443418, 44.016091], [-79.446567, 44.019296], [-79.448821, 44.019023], [-79.451846, 44.018652], [-79.455019, 44.017014], [-79.453243, 44.016353], [-79.451009, 44.016442], [-79.450156, 44.014795], [-79.45309, 44.013818], [-79.454578, 44.012761], [-79.454141, 44.011242], [-79.451327, 44.01136]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_b84f190ef43d4eedd120ec2120af8580.bindTooltip(
                `<div>
                     426 DR G.W. WILLIAMS SS VIA HOLLIDGE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_b84f190ef43d4eedd120ec2120af8580.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_83b1d10217dca1240032dba5be48f516_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_83b1d10217dca1240032dba5be48f516_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_83b1d10217dca1240032dba5be48f516 = L.geoJson(null, {
                onEachFeature: geo_json_83b1d10217dca1240032dba5be48f516_onEachFeature,
            
                style: geo_json_83b1d10217dca1240032dba5be48f516_styler,
            ...{
}
        });

        function geo_json_83b1d10217dca1240032dba5be48f516_add (data) {
            geo_json_83b1d10217dca1240032dba5be48f516
                .addData(data);
        }
            geo_json_83b1d10217dca1240032dba5be48f516_add({"features": [{"geometry": {"coordinates": [[-79.447708, 44.023449], [-79.448108, 44.025081], [-79.449047, 44.029116], [-79.44999, 44.033276], [-79.449371, 44.033512], [-79.444084, 44.035054], [-79.438468, 44.035753], [-79.435627, 44.035932], [-79.430333, 44.036012], [-79.425749, 44.037166], [-79.420978, 44.037928], [-79.420665, 44.039136], [-79.418104, 44.038309], [-79.418745, 44.03683], [-79.422669, 44.037965], [-79.42581, 44.040487], [-79.426365, 44.042877], [-79.428753, 44.047287], [-79.434646, 44.04598], [-79.437716, 44.045312], [-79.446418, 44.043226], [-79.451657, 44.041408], [-79.452388, 44.043426], [-79.453192, 44.04677], [-79.452896, 44.049378], [-79.450597, 44.051994], [-79.445975, 44.053067], [-79.441149, 44.054156], [-79.441008, 44.057857]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_83b1d10217dca1240032dba5be48f516.bindTooltip(
                `<div>
                     427 SACRED HEART SS VIA STONEHAVEN
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_83b1d10217dca1240032dba5be48f516.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_d1b7ab2273f285c06d0a01ae422d694b_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_d1b7ab2273f285c06d0a01ae422d694b_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_d1b7ab2273f285c06d0a01ae422d694b = L.geoJson(null, {
                onEachFeature: geo_json_d1b7ab2273f285c06d0a01ae422d694b_onEachFeature,
            
                style: geo_json_d1b7ab2273f285c06d0a01ae422d694b_styler,
            ...{
}
        });

        function geo_json_d1b7ab2273f285c06d0a01ae422d694b_add (data) {
            geo_json_d1b7ab2273f285c06d0a01ae422d694b
                .addData(data);
        }
            geo_json_d1b7ab2273f285c06d0a01ae422d694b_add({"features": [{"geometry": {"coordinates": [[-79.435883, 44.057806], [-79.447852, 44.059755], [-79.453002, 44.049624], [-79.45343, 44.047013], [-79.452594, 44.043727], [-79.449653, 44.041436], [-79.446665, 44.042756], [-79.435186, 44.047194], [-79.427752, 44.047238], [-79.42672, 44.043302], [-79.420978, 44.037928], [-79.420665, 44.039136], [-79.418104, 44.038309], [-79.418745, 44.03683], [-79.422669, 44.037965], [-79.425958, 44.037307], [-79.429962, 44.036146], [-79.435178, 44.036012], [-79.438153, 44.035854], [-79.439762, 44.035795], [-79.443794, 44.035078], [-79.447634, 44.034257], [-79.449452, 44.029585], [-79.448687, 44.026176], [-79.448128, 44.023681]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_d1b7ab2273f285c06d0a01ae422d694b.bindTooltip(
                `<div>
                     427 SACRED HEART SS VIA STONEHAVEN
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_d1b7ab2273f285c06d0a01ae422d694b.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_13da294d3d868ecb701311d330d7abd2_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_13da294d3d868ecb701311d330d7abd2_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_13da294d3d868ecb701311d330d7abd2 = L.geoJson(null, {
                onEachFeature: geo_json_13da294d3d868ecb701311d330d7abd2_onEachFeature,
            
                style: geo_json_13da294d3d868ecb701311d330d7abd2_styler,
            ...{
}
        });

        function geo_json_13da294d3d868ecb701311d330d7abd2_add (data) {
            geo_json_13da294d3d868ecb701311d330d7abd2
                .addData(data);
        }
            geo_json_13da294d3d868ecb701311d330d7abd2_add({"features": [{"geometry": {"coordinates": [[-79.463224, 43.990875], [-79.460133, 43.984854], [-79.462698, 43.983985], [-79.464687, 43.983672], [-79.465704, 43.982432], [-79.467386, 43.980432], [-79.470662, 43.979728], [-79.476532, 43.978415], [-79.476003, 43.976142], [-79.475298, 43.973752], [-79.477595, 43.972922], [-79.479934, 43.971893], [-79.482522, 43.970926], [-79.484866, 43.970856], [-79.487991, 43.970409], [-79.489479, 43.973518], [-79.489746, 43.975434], [-79.486677, 43.976113], [-79.480634, 43.977445]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_13da294d3d868ecb701311d330d7abd2.bindTooltip(
                `<div>
                     428 DR G.W. WILLIAMS SS VIA HENDERSON
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_13da294d3d868ecb701311d330d7abd2.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_a6dc4d7a5a55145131bb2fe710db985b_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_a6dc4d7a5a55145131bb2fe710db985b_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_a6dc4d7a5a55145131bb2fe710db985b = L.geoJson(null, {
                onEachFeature: geo_json_a6dc4d7a5a55145131bb2fe710db985b_onEachFeature,
            
                style: geo_json_a6dc4d7a5a55145131bb2fe710db985b_styler,
            ...{
}
        });

        function geo_json_a6dc4d7a5a55145131bb2fe710db985b_add (data) {
            geo_json_a6dc4d7a5a55145131bb2fe710db985b
                .addData(data);
        }
            geo_json_a6dc4d7a5a55145131bb2fe710db985b_add({"features": [{"geometry": {"coordinates": [[-79.429576, 43.940148], [-79.430848, 43.940212], [-79.434033, 43.93932], [-79.438132, 43.939162], [-79.441791, 43.938597], [-79.44726, 43.939313], [-79.453278, 43.939973], [-79.453832, 43.941634], [-79.454238, 43.943311], [-79.453234, 43.943385], [-79.449758, 43.94291], [-79.446073, 43.942737], [-79.443019, 43.943294], [-79.436848, 43.944679], [-79.434212, 43.945212], [-79.431386, 43.946053], [-79.427738, 43.949958], [-79.432939, 43.957827], [-79.435477, 43.962286], [-79.43867, 43.961643], [-79.441983, 43.960823], [-79.443442, 43.96341], [-79.441884, 43.96603], [-79.435559, 43.967767], [-79.434238, 43.96276], [-79.433298, 43.958533], [-79.432348, 43.954521], [-79.432413, 43.953954], [-79.434733, 43.953429], [-79.436894, 43.952947], [-79.438964, 43.952204], [-79.441043, 43.951616], [-79.448765, 43.948173], [-79.455386, 43.948224], [-79.454413, 43.948567], [-79.4516, 43.951657], [-79.446542, 43.953097], [-79.451732, 43.955453], [-79.45675, 43.955085], [-79.457668, 43.958441], [-79.460265, 43.958806], [-79.462958, 43.958204], [-79.466556, 43.95742], [-79.469684, 43.957923], [-79.471039, 43.960064], [-79.468053, 43.960993], [-79.459508, 43.962763], [-79.458209, 43.959468], [-79.460265, 43.958806], [-79.462958, 43.958204], [-79.466556, 43.95742], [-79.469684, 43.957923], [-79.471039, 43.960064], [-79.477334, 43.958992], [-79.480932, 43.958214], [-79.484338, 43.957824], [-79.485718, 43.95873], [-79.488588, 43.96962], [-79.489479, 43.973518], [-79.489746, 43.975434], [-79.49261, 43.994279], [-79.487041, 43.995373], [-79.483445, 43.996087], [-79.479627, 43.996918], [-79.476131, 43.99769]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_a6dc4d7a5a55145131bb2fe710db985b.bindTooltip(
                `<div>
                     429 CARDINAL CARTER / AURORA SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_a6dc4d7a5a55145131bb2fe710db985b.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_0337971f9ec2c3792735660f255b77ff_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_0337971f9ec2c3792735660f255b77ff_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_0337971f9ec2c3792735660f255b77ff = L.geoJson(null, {
                onEachFeature: geo_json_0337971f9ec2c3792735660f255b77ff_onEachFeature,
            
                style: geo_json_0337971f9ec2c3792735660f255b77ff_styler,
            ...{
}
        });

        function geo_json_0337971f9ec2c3792735660f255b77ff_add (data) {
            geo_json_0337971f9ec2c3792735660f255b77ff
                .addData(data);
        }
            geo_json_0337971f9ec2c3792735660f255b77ff_add({"features": [{"geometry": {"coordinates": [[-79.467437, 43.961294], [-79.471171, 43.959879], [-79.469794, 43.957797], [-79.466774, 43.957493], [-79.462977, 43.958064], [-79.460567, 43.958645], [-79.458288, 43.959159], [-79.455648, 43.954934], [-79.452865, 43.955097], [-79.448586, 43.955554], [-79.447415, 43.952631], [-79.451463, 43.951984], [-79.454625, 43.948678], [-79.454569, 43.94665], [-79.451443, 43.947338], [-79.448115, 43.948083], [-79.4436, 43.949059], [-79.439451, 43.952004], [-79.436636, 43.952912], [-79.434831, 43.953313], [-79.432681, 43.953778], [-79.432939, 43.957827], [-79.435477, 43.962286], [-79.43867, 43.961643], [-79.441983, 43.960823], [-79.443442, 43.96341], [-79.441884, 43.96603], [-79.435559, 43.967767], [-79.434238, 43.96276], [-79.433298, 43.958533], [-79.432348, 43.954521], [-79.428141, 43.950389], [-79.42753, 43.946294], [-79.428498, 43.943388], [-79.429576, 43.940148], [-79.430848, 43.940212], [-79.434033, 43.93932], [-79.438132, 43.939162], [-79.441791, 43.938597], [-79.44726, 43.939313], [-79.453278, 43.939973], [-79.453832, 43.941634], [-79.454238, 43.943311], [-79.453234, 43.943385], [-79.449758, 43.94291], [-79.446073, 43.942737], [-79.443019, 43.943294], [-79.436848, 43.944679], [-79.434212, 43.945212], [-79.431386, 43.946053]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_0337971f9ec2c3792735660f255b77ff.bindTooltip(
                `<div>
                     429 CARDINAL CARTER / AURORA SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_0337971f9ec2c3792735660f255b77ff.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_ccb75335a6dd3380831b41b793f1ab4e_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_ccb75335a6dd3380831b41b793f1ab4e_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_ccb75335a6dd3380831b41b793f1ab4e = L.geoJson(null, {
                onEachFeature: geo_json_ccb75335a6dd3380831b41b793f1ab4e_onEachFeature,
            
                style: geo_json_ccb75335a6dd3380831b41b793f1ab4e_styler,
            ...{
}
        });

        function geo_json_ccb75335a6dd3380831b41b793f1ab4e_add (data) {
            geo_json_ccb75335a6dd3380831b41b793f1ab4e
                .addData(data);
        }
            geo_json_ccb75335a6dd3380831b41b793f1ab4e_add({"features": [{"geometry": {"coordinates": [[-79.487097, 44.052926], [-79.490529, 44.052823], [-79.496797, 44.051409], [-79.497916, 44.052841], [-79.499455, 44.056179], [-79.495708, 44.056696], [-79.493721, 44.058153], [-79.492169, 44.059548], [-79.492496, 44.062926], [-79.493228, 44.065905], [-79.493773, 44.068252], [-79.493941, 44.070713], [-79.485451, 44.072654], [-79.484559, 44.071102], [-79.482029, 44.068211], [-79.477738, 44.068247], [-79.480668, 44.065889], [-79.475877, 44.063788], [-79.47344, 44.064379], [-79.471127, 44.065142], [-79.468969, 44.067164], [-79.469509, 44.069019], [-79.467206, 44.070437], [-79.465096, 44.072303], [-79.462259, 44.072955], [-79.459356, 44.073619], [-79.45909, 44.070083], [-79.459931, 44.068101], [-79.462935, 44.064472], [-79.462556, 44.062077], [-79.46145, 44.05948], [-79.460903, 44.058284], [-79.459746, 44.056296], [-79.457357, 44.053179], [-79.454794, 44.051511], [-79.450597, 44.051994], [-79.445975, 44.053067], [-79.441008, 44.057857]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_ccb75335a6dd3380831b41b793f1ab4e.bindTooltip(
                `<div>
                     430 SACRED HEART SS VIA MAIN
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_ccb75335a6dd3380831b41b793f1ab4e.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_f0c5acb9961db7038539ba7a763dc5f6_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_f0c5acb9961db7038539ba7a763dc5f6_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_f0c5acb9961db7038539ba7a763dc5f6 = L.geoJson(null, {
                onEachFeature: geo_json_f0c5acb9961db7038539ba7a763dc5f6_onEachFeature,
            
                style: geo_json_f0c5acb9961db7038539ba7a763dc5f6_styler,
            ...{
}
        });

        function geo_json_f0c5acb9961db7038539ba7a763dc5f6_add (data) {
            geo_json_f0c5acb9961db7038539ba7a763dc5f6
                .addData(data);
        }
            geo_json_f0c5acb9961db7038539ba7a763dc5f6_add({"features": [{"geometry": {"coordinates": [[-79.440337, 44.058089], [-79.441474, 44.054233], [-79.444792, 44.053445], [-79.450817, 44.052042], [-79.453016, 44.051621], [-79.454926, 44.051653], [-79.457136, 44.053066], [-79.459367, 44.056068], [-79.46096, 44.05896], [-79.462242, 44.061675], [-79.463102, 44.063907], [-79.459733, 44.067652], [-79.459095, 44.0698], [-79.458835, 44.072564], [-79.45991, 44.073591], [-79.467017, 44.070604], [-79.468888, 44.067387], [-79.470899, 44.065514], [-79.473182, 44.064527], [-79.475497, 44.064005], [-79.480459, 44.065686], [-79.477555, 44.068125], [-79.482334, 44.068282], [-79.484137, 44.070723], [-79.493859, 44.06982], [-79.493962, 44.067797], [-79.493402, 44.065866], [-79.492756, 44.063214], [-79.492302, 44.059879], [-79.493416, 44.058609], [-79.496079, 44.056725], [-79.499746, 44.056254], [-79.498437, 44.053066], [-79.491139, 44.052399], [-79.487097, 44.052926]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_f0c5acb9961db7038539ba7a763dc5f6.bindTooltip(
                `<div>
                     430 SACRED HEART SS VIA MAIN
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_f0c5acb9961db7038539ba7a763dc5f6.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_b3236e617d05bd6dc4009c52984bfaff_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_b3236e617d05bd6dc4009c52984bfaff_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_b3236e617d05bd6dc4009c52984bfaff = L.geoJson(null, {
                onEachFeature: geo_json_b3236e617d05bd6dc4009c52984bfaff_onEachFeature,
            
                style: geo_json_b3236e617d05bd6dc4009c52984bfaff_styler,
            ...{
}
        });

        function geo_json_b3236e617d05bd6dc4009c52984bfaff_add (data) {
            geo_json_b3236e617d05bd6dc4009c52984bfaff
                .addData(data);
        }
            geo_json_b3236e617d05bd6dc4009c52984bfaff_add({"features": [{"geometry": {"coordinates": [[-79.45109, 44.003907], [-79.45028, 44.006021], [-79.449795, 44.008027], [-79.450217, 44.009352], [-79.450828, 44.011154], [-79.453509, 44.011232], [-79.454444, 44.012698], [-79.453043, 44.013702], [-79.450209, 44.014549], [-79.450337, 44.016159], [-79.452978, 44.016544], [-79.454865, 44.016979], [-79.455447, 44.018376], [-79.456116, 44.019957], [-79.45659, 44.02119], [-79.451021, 44.02253], [-79.448414, 44.023379], [-79.443575, 44.024455], [-79.442719, 44.023146], [-79.440675, 44.020662], [-79.439456, 44.017566], [-79.437764, 44.015584], [-79.436851, 44.014336], [-79.435642, 44.011674], [-79.434586, 44.009569], [-79.433601, 44.007819], [-79.439224, 44.0063], [-79.443617, 44.005262], [-79.444889, 44.004867], [-79.450674, 44.003497], [-79.452112, 44.003147], [-79.454002, 44.002749], [-79.457317, 44.002018], [-79.460502, 44.001278], [-79.463921, 44.000489], [-79.467392, 43.999805], [-79.468527, 43.999496], [-79.472162, 43.998714], [-79.475881, 43.997919], [-79.480009, 43.997046]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_b3236e617d05bd6dc4009c52984bfaff.bindTooltip(
                `<div>
                     432 AURORA SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_b3236e617d05bd6dc4009c52984bfaff.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_1ca5490cb6d09c904b20c0815d2ffc89_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_1ca5490cb6d09c904b20c0815d2ffc89_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_1ca5490cb6d09c904b20c0815d2ffc89 = L.geoJson(null, {
                onEachFeature: geo_json_1ca5490cb6d09c904b20c0815d2ffc89_onEachFeature,
            
                style: geo_json_1ca5490cb6d09c904b20c0815d2ffc89_styler,
            ...{
}
        });

        function geo_json_1ca5490cb6d09c904b20c0815d2ffc89_add (data) {
            geo_json_1ca5490cb6d09c904b20c0815d2ffc89
                .addData(data);
        }
            geo_json_1ca5490cb6d09c904b20c0815d2ffc89_add({"features": [{"geometry": {"coordinates": [[-79.480009, 43.997046], [-79.477347, 43.999173], [-79.476315, 43.998281], [-79.472723, 43.998455], [-79.46832, 43.999445], [-79.465904, 43.999965], [-79.464299, 44.000311], [-79.460693, 44.001138], [-79.456992, 44.001909], [-79.45109, 44.003907], [-79.45028, 44.006021], [-79.449795, 44.008027], [-79.450217, 44.009352], [-79.450828, 44.011154], [-79.453509, 44.011232], [-79.454444, 44.012698], [-79.453043, 44.013702], [-79.450209, 44.014549], [-79.450337, 44.016159], [-79.452978, 44.016544], [-79.454865, 44.016979], [-79.455447, 44.018376], [-79.456116, 44.019957], [-79.45659, 44.02119], [-79.451021, 44.02253], [-79.448414, 44.023379], [-79.443575, 44.024455], [-79.442719, 44.023146], [-79.440675, 44.020662], [-79.439456, 44.017566], [-79.437764, 44.015584], [-79.436851, 44.014336], [-79.435642, 44.011674], [-79.434586, 44.009569], [-79.433601, 44.007819], [-79.439224, 44.0063], [-79.442997, 44.001094], [-79.442175, 43.994272], [-79.444056, 43.993853], [-79.446044, 43.993405], [-79.447185, 43.993501], [-79.449104, 43.994221], [-79.447388, 43.997306], [-79.445564, 43.998905], [-79.443694, 44.000706]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_1ca5490cb6d09c904b20c0815d2ffc89.bindTooltip(
                `<div>
                     432 AURORA SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_1ca5490cb6d09c904b20c0815d2ffc89.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_5b33f587b0ad2e17b2ad65d03cedbbce_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_5b33f587b0ad2e17b2ad65d03cedbbce_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_5b33f587b0ad2e17b2ad65d03cedbbce = L.geoJson(null, {
                onEachFeature: geo_json_5b33f587b0ad2e17b2ad65d03cedbbce_onEachFeature,
            
                style: geo_json_5b33f587b0ad2e17b2ad65d03cedbbce_styler,
            ...{
}
        });

        function geo_json_5b33f587b0ad2e17b2ad65d03cedbbce_add (data) {
            geo_json_5b33f587b0ad2e17b2ad65d03cedbbce
                .addData(data);
        }
            geo_json_5b33f587b0ad2e17b2ad65d03cedbbce_add({"features": [{"geometry": {"coordinates": [[-79.481791, 43.938772], [-79.480766, 43.935695], [-79.476921, 43.931873], [-79.474139, 43.932449], [-79.471961, 43.933382], [-79.47268, 43.936602], [-79.473005, 43.937589], [-79.47124, 43.938256], [-79.469, 43.938838], [-79.466909, 43.939371], [-79.464484, 43.9399], [-79.461007, 43.940642], [-79.459911, 43.939601], [-79.457438, 43.939614], [-79.454392, 43.939652], [-79.453832, 43.941634], [-79.454238, 43.943311], [-79.454715, 43.945095], [-79.455386, 43.948224], [-79.455859, 43.950171], [-79.456268, 43.951671], [-79.456841, 43.954832], [-79.457668, 43.958441], [-79.459865, 43.962912], [-79.467437, 43.961294]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_5b33f587b0ad2e17b2ad65d03cedbbce.bindTooltip(
                `<div>
                     433 CARDINAL CARTER SS VIA KINGSHILL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_5b33f587b0ad2e17b2ad65d03cedbbce.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_48b77e8ea62b5d1f51c0cd5c73840f03_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_48b77e8ea62b5d1f51c0cd5c73840f03_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_48b77e8ea62b5d1f51c0cd5c73840f03 = L.geoJson(null, {
                onEachFeature: geo_json_48b77e8ea62b5d1f51c0cd5c73840f03_onEachFeature,
            
                style: geo_json_48b77e8ea62b5d1f51c0cd5c73840f03_styler,
            ...{
}
        });

        function geo_json_48b77e8ea62b5d1f51c0cd5c73840f03_add (data) {
            geo_json_48b77e8ea62b5d1f51c0cd5c73840f03
                .addData(data);
        }
            geo_json_48b77e8ea62b5d1f51c0cd5c73840f03_add({"features": [{"geometry": {"coordinates": [[-79.468053, 43.960993], [-79.459508, 43.962763], [-79.458209, 43.959468], [-79.457341, 43.955254], [-79.456443, 43.951598], [-79.456186, 43.950338], [-79.455809, 43.948727], [-79.45532, 43.946664], [-79.45489, 43.944757], [-79.454291, 43.942266], [-79.453825, 43.940082], [-79.457876, 43.939618], [-79.459792, 43.939599], [-79.461001, 43.940723], [-79.464633, 43.93997], [-79.466677, 43.939548], [-79.468636, 43.939085], [-79.470995, 43.938396], [-79.47308, 43.937954], [-79.472846, 43.936766], [-79.47187, 43.933946], [-79.473762, 43.932609], [-79.47634, 43.932069], [-79.479102, 43.931499], [-79.480246, 43.934876], [-79.480794, 43.937106]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_48b77e8ea62b5d1f51c0cd5c73840f03.bindTooltip(
                `<div>
                     433 CARDINAL CARTER SS VIA KINGSHILL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_48b77e8ea62b5d1f51c0cd5c73840f03.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_ebaf19a91bde5b6aba4351930ac149e5_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_ebaf19a91bde5b6aba4351930ac149e5_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_ebaf19a91bde5b6aba4351930ac149e5 = L.geoJson(null, {
                onEachFeature: geo_json_ebaf19a91bde5b6aba4351930ac149e5_onEachFeature,
            
                style: geo_json_ebaf19a91bde5b6aba4351930ac149e5_styler,
            ...{
}
        });

        function geo_json_ebaf19a91bde5b6aba4351930ac149e5_add (data) {
            geo_json_ebaf19a91bde5b6aba4351930ac149e5
                .addData(data);
        }
            geo_json_ebaf19a91bde5b6aba4351930ac149e5_add({"features": [{"geometry": {"coordinates": [[-79.442997, 44.001094], [-79.442175, 43.994272], [-79.444056, 43.993853], [-79.446044, 43.993405], [-79.447185, 43.993501], [-79.449104, 43.994221], [-79.447388, 43.997306], [-79.445564, 43.998905], [-79.443694, 44.000706], [-79.444889, 44.004867], [-79.450674, 44.003497], [-79.452112, 44.003147], [-79.454002, 44.002749], [-79.457317, 44.002018], [-79.460502, 44.001278], [-79.463921, 44.000489], [-79.467392, 43.999805], [-79.468527, 43.999496], [-79.472162, 43.998714], [-79.475881, 43.997919], [-79.480009, 43.997046], [-79.483089, 43.996381], [-79.486704, 43.995639], [-79.492878, 43.994429], [-79.4924, 43.989096], [-79.487749, 43.989356], [-79.485338, 43.989813], [-79.481856, 43.990575], [-79.48015, 43.990984], [-79.476192, 43.988621], [-79.476161, 43.985275], [-79.474501, 43.983615], [-79.469866, 43.984286], [-79.466976, 43.986094], [-79.464771, 43.986522], [-79.460181, 43.987588], [-79.460133, 43.984854], [-79.462698, 43.983985], [-79.464687, 43.983672], [-79.465704, 43.982432], [-79.467386, 43.980432], [-79.470662, 43.979728], [-79.476532, 43.978415], [-79.476003, 43.976142], [-79.475298, 43.973752], [-79.477595, 43.972922], [-79.479934, 43.971893], [-79.482522, 43.970926], [-79.484866, 43.970856], [-79.487991, 43.970409], [-79.481518, 43.957955], [-79.477582, 43.958791], [-79.471645, 43.960108], [-79.468053, 43.960993]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_ebaf19a91bde5b6aba4351930ac149e5.bindTooltip(
                `<div>
                     434 CARDINAL CARTER SS VIA WELLINGTON
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_ebaf19a91bde5b6aba4351930ac149e5.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_cd896b3a01695ca75c98dc790c4e5fa0_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_cd896b3a01695ca75c98dc790c4e5fa0_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_cd896b3a01695ca75c98dc790c4e5fa0 = L.geoJson(null, {
                onEachFeature: geo_json_cd896b3a01695ca75c98dc790c4e5fa0_onEachFeature,
            
                style: geo_json_cd896b3a01695ca75c98dc790c4e5fa0_styler,
            ...{
}
        });

        function geo_json_cd896b3a01695ca75c98dc790c4e5fa0_add (data) {
            geo_json_cd896b3a01695ca75c98dc790c4e5fa0
                .addData(data);
        }
            geo_json_cd896b3a01695ca75c98dc790c4e5fa0_add({"features": [{"geometry": {"coordinates": [[-79.467437, 43.961294], [-79.471117, 43.960436], [-79.477334, 43.958992], [-79.480932, 43.958214], [-79.484338, 43.957824], [-79.485718, 43.95873], [-79.488588, 43.96962], [-79.487964, 43.970239], [-79.485163, 43.970752], [-79.480294, 43.971525], [-79.477897, 43.972773], [-79.475691, 43.975911], [-79.470367, 43.97965], [-79.467968, 43.980168], [-79.465463, 43.981815], [-79.463939, 43.983659], [-79.462513, 43.983904], [-79.460005, 43.984794], [-79.459742, 43.987457], [-79.461196, 43.987513], [-79.46417, 43.986829], [-79.466712, 43.986255], [-79.469534, 43.984529], [-79.471923, 43.983832], [-79.47412, 43.983653], [-79.47556, 43.98439], [-79.475993, 43.988578], [-79.479888, 43.990941], [-79.482308, 43.990577], [-79.484897, 43.989993], [-79.487372, 43.989464], [-79.489872, 43.989468], [-79.492884, 43.989197], [-79.49261, 43.994279], [-79.487041, 43.995373], [-79.483445, 43.996087], [-79.479627, 43.996918], [-79.476131, 43.99769], [-79.472723, 43.998455], [-79.46832, 43.999445], [-79.465904, 43.999965], [-79.464299, 44.000311], [-79.460693, 44.001138], [-79.456992, 44.001909], [-79.451138, 44.003193], [-79.444109, 44.004852], [-79.442997, 44.001094], [-79.442175, 43.994272], [-79.444056, 43.993853], [-79.446044, 43.993405], [-79.447185, 43.993501], [-79.449104, 43.994221], [-79.447388, 43.997306], [-79.445564, 43.998905], [-79.443694, 44.000706]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_cd896b3a01695ca75c98dc790c4e5fa0.bindTooltip(
                `<div>
                     434 CARDINAL CARTER SS VIA WELLINGTON
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_cd896b3a01695ca75c98dc790c4e5fa0.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_27814d1a4751ab8cf99d676204ceabd5_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_27814d1a4751ab8cf99d676204ceabd5_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_27814d1a4751ab8cf99d676204ceabd5 = L.geoJson(null, {
                onEachFeature: geo_json_27814d1a4751ab8cf99d676204ceabd5_onEachFeature,
            
                style: geo_json_27814d1a4751ab8cf99d676204ceabd5_styler,
            ...{
}
        });

        function geo_json_27814d1a4751ab8cf99d676204ceabd5_add (data) {
            geo_json_27814d1a4751ab8cf99d676204ceabd5
                .addData(data);
        }
            geo_json_27814d1a4751ab8cf99d676204ceabd5_add({"features": [{"geometry": {"coordinates": [[-79.455442, 43.944515], [-79.458255, 43.943957], [-79.463956, 43.942742], [-79.464921, 43.944767], [-79.465515, 43.946208], [-79.466178, 43.947885], [-79.469025, 43.950879], [-79.471868, 43.9509], [-79.47634, 43.950084], [-79.479139, 43.949907], [-79.483119, 43.950797], [-79.484461, 43.953387], [-79.485222, 43.956773], [-79.481518, 43.957955], [-79.477582, 43.958791], [-79.471645, 43.960108], [-79.468053, 43.960993]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_27814d1a4751ab8cf99d676204ceabd5.bindTooltip(
                `<div>
                     436 CARDINAL CARTER SS VIA PARKER
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_27814d1a4751ab8cf99d676204ceabd5.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_4aadf6446ea58f7836dcc989323890fa_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_4aadf6446ea58f7836dcc989323890fa_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_4aadf6446ea58f7836dcc989323890fa = L.geoJson(null, {
                onEachFeature: geo_json_4aadf6446ea58f7836dcc989323890fa_onEachFeature,
            
                style: geo_json_4aadf6446ea58f7836dcc989323890fa_styler,
            ...{
}
        });

        function geo_json_4aadf6446ea58f7836dcc989323890fa_add (data) {
            geo_json_4aadf6446ea58f7836dcc989323890fa
                .addData(data);
        }
            geo_json_4aadf6446ea58f7836dcc989323890fa_add({"features": [{"geometry": {"coordinates": [[-79.468053, 43.960993], [-79.459508, 43.962763], [-79.458209, 43.959468], [-79.457341, 43.955254], [-79.456186, 43.950338], [-79.455809, 43.948727], [-79.45532, 43.946664], [-79.45489, 43.944757], [-79.455442, 43.944515], [-79.458255, 43.943957], [-79.463956, 43.942742], [-79.464921, 43.944767], [-79.465515, 43.946208], [-79.466178, 43.947885], [-79.469025, 43.950879], [-79.471868, 43.9509], [-79.47634, 43.950084], [-79.479139, 43.949907], [-79.483119, 43.950797], [-79.484461, 43.953387], [-79.485222, 43.956773]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_4aadf6446ea58f7836dcc989323890fa.bindTooltip(
                `<div>
                     436 CARDINAL CARTER SS VIA PARKER
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_4aadf6446ea58f7836dcc989323890fa.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_4edd37a8dc7c8644277b4f4ef8537271_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_4edd37a8dc7c8644277b4f4ef8537271_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_4edd37a8dc7c8644277b4f4ef8537271 = L.geoJson(null, {
                onEachFeature: geo_json_4edd37a8dc7c8644277b4f4ef8537271_onEachFeature,
            
                style: geo_json_4edd37a8dc7c8644277b4f4ef8537271_styler,
            ...{
}
        });

        function geo_json_4edd37a8dc7c8644277b4f4ef8537271_add (data) {
            geo_json_4edd37a8dc7c8644277b4f4ef8537271
                .addData(data);
        }
            geo_json_4edd37a8dc7c8644277b4f4ef8537271_add({"features": [{"geometry": {"coordinates": [[-79.420978, 44.037928], [-79.420665, 44.039136], [-79.418104, 44.038309], [-79.418745, 44.03683], [-79.422669, 44.037965], [-79.424436, 44.034558], [-79.422966, 44.029218], [-79.442719, 44.023146], [-79.440675, 44.020662], [-79.439456, 44.017566], [-79.437764, 44.015584], [-79.436851, 44.014336], [-79.435642, 44.011674], [-79.434586, 44.009569], [-79.433601, 44.007819], [-79.425768, 44.009053], [-79.418834, 44.011629], [-79.419666, 44.015713], [-79.421271, 44.019661], [-79.425325, 44.019195], [-79.427657, 44.020871], [-79.428978, 44.023616], [-79.429987, 44.025147], [-79.45048, 44.022925], [-79.456438, 44.020335], [-79.455763, 44.018744], [-79.455019, 44.017014], [-79.453243, 44.016353], [-79.451009, 44.016442], [-79.450156, 44.014795], [-79.45309, 44.013818], [-79.454578, 44.012761], [-79.454141, 44.011242], [-79.451327, 44.01136], [-79.450634, 44.010099], [-79.450093, 44.008411], [-79.449775, 44.007526], [-79.4508, 44.005608], [-79.451138, 44.003543], [-79.452112, 44.003147], [-79.454002, 44.002749]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_4edd37a8dc7c8644277b4f4ef8537271.bindTooltip(
                `<div>
                     437 ST MAXIMILIAN KOLBE SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_4edd37a8dc7c8644277b4f4ef8537271.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_1765a47537748655ad648b331a1deac9_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_1765a47537748655ad648b331a1deac9_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_1765a47537748655ad648b331a1deac9 = L.geoJson(null, {
                onEachFeature: geo_json_1765a47537748655ad648b331a1deac9_onEachFeature,
            
                style: geo_json_1765a47537748655ad648b331a1deac9_styler,
            ...{
}
        });

        function geo_json_1765a47537748655ad648b331a1deac9_add (data) {
            geo_json_1765a47537748655ad648b331a1deac9
                .addData(data);
        }
            geo_json_1765a47537748655ad648b331a1deac9_add({"features": [{"geometry": {"coordinates": [[-79.454002, 44.002749], [-79.450745, 44.00318], [-79.45109, 44.003907], [-79.45028, 44.006021], [-79.449795, 44.008027], [-79.450217, 44.009352], [-79.450828, 44.011154], [-79.453509, 44.011232], [-79.454444, 44.012698], [-79.453043, 44.013702], [-79.450209, 44.014549], [-79.450337, 44.016159], [-79.452978, 44.016544], [-79.454865, 44.016979], [-79.455447, 44.018376], [-79.456116, 44.019957], [-79.45659, 44.02119], [-79.451021, 44.02253], [-79.448414, 44.023379], [-79.443575, 44.024455], [-79.442719, 44.023146], [-79.440675, 44.020662], [-79.439456, 44.017566], [-79.437764, 44.015584], [-79.436851, 44.014336], [-79.435642, 44.011674], [-79.434586, 44.009569], [-79.433601, 44.007819], [-79.425768, 44.009053], [-79.418834, 44.011629], [-79.419666, 44.015713], [-79.421271, 44.019661], [-79.425325, 44.019195], [-79.427657, 44.020871], [-79.428978, 44.023616], [-79.429987, 44.025147], [-79.430694, 44.026957], [-79.424386, 44.035379], [-79.420978, 44.037928], [-79.420665, 44.039136], [-79.418104, 44.038309], [-79.418745, 44.03683], [-79.422669, 44.037965]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_1765a47537748655ad648b331a1deac9.bindTooltip(
                `<div>
                     437 ST MAXIMILIAN KOLBE SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_1765a47537748655ad648b331a1deac9.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_d9cd0234cc5a6d24a0b26643c28925d7_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_d9cd0234cc5a6d24a0b26643c28925d7_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_d9cd0234cc5a6d24a0b26643c28925d7 = L.geoJson(null, {
                onEachFeature: geo_json_d9cd0234cc5a6d24a0b26643c28925d7_onEachFeature,
            
                style: geo_json_d9cd0234cc5a6d24a0b26643c28925d7_styler,
            ...{
}
        });

        function geo_json_d9cd0234cc5a6d24a0b26643c28925d7_add (data) {
            geo_json_d9cd0234cc5a6d24a0b26643c28925d7
                .addData(data);
        }
            geo_json_d9cd0234cc5a6d24a0b26643c28925d7_add({"features": [{"geometry": {"coordinates": [[-79.430896, 43.877592], [-79.433889, 43.879107], [-79.435653, 43.878666], [-79.438628, 43.878073], [-79.441748, 43.877472], [-79.444441, 43.877457], [-79.448088, 43.876712], [-79.451059, 43.87608], [-79.454363, 43.875387], [-79.456274, 43.874972], [-79.460058, 43.874171], [-79.460349, 43.875901], [-79.461911, 43.877568], [-79.462097, 43.878953], [-79.459067, 43.880494], [-79.456888, 43.880906], [-79.453652, 43.880399], [-79.450985, 43.881129], [-79.451475, 43.88466], [-79.452059, 43.886842], [-79.457556, 43.886255], [-79.460382, 43.885606], [-79.463536, 43.884979], [-79.466976, 43.884296], [-79.468179, 43.888451], [-79.469466, 43.893874]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_d9cd0234cc5a6d24a0b26643c28925d7.bindTooltip(
                `<div>
                     440 ST THERESA SS VIA MILL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_d9cd0234cc5a6d24a0b26643c28925d7.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_0e0c73915cc5b0ad262383f1a7586c81_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_0e0c73915cc5b0ad262383f1a7586c81_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_0e0c73915cc5b0ad262383f1a7586c81 = L.geoJson(null, {
                onEachFeature: geo_json_0e0c73915cc5b0ad262383f1a7586c81_onEachFeature,
            
                style: geo_json_0e0c73915cc5b0ad262383f1a7586c81_styler,
            ...{
}
        });

        function geo_json_0e0c73915cc5b0ad262383f1a7586c81_add (data) {
            geo_json_0e0c73915cc5b0ad262383f1a7586c81
                .addData(data);
        }
            geo_json_0e0c73915cc5b0ad262383f1a7586c81_add({"features": [{"geometry": {"coordinates": [[-79.468936, 43.894405], [-79.466513, 43.884222], [-79.462686, 43.884967], [-79.460766, 43.885405], [-79.457958, 43.886002], [-79.45251, 43.887152], [-79.451736, 43.88496], [-79.450972, 43.881431], [-79.45457, 43.880639], [-79.456523, 43.88098], [-79.458798, 43.880694], [-79.462375, 43.879029], [-79.462131, 43.877554], [-79.460569, 43.876119], [-79.459573, 43.874179], [-79.456629, 43.874836], [-79.454703, 43.875247], [-79.451593, 43.875865], [-79.448258, 43.876608], [-79.444782, 43.877321], [-79.442031, 43.877601], [-79.439378, 43.877887], [-79.437834, 43.87811], [-79.435573, 43.878601], [-79.433623, 43.879104], [-79.432612, 43.877247], [-79.430827, 43.877515]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_0e0c73915cc5b0ad262383f1a7586c81.bindTooltip(
                `<div>
                     440 ST THERESA SS VIA MILL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_0e0c73915cc5b0ad262383f1a7586c81.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_3e2b8cc6a8a7184f73f012a76b321db1_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_3e2b8cc6a8a7184f73f012a76b321db1_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_3e2b8cc6a8a7184f73f012a76b321db1 = L.geoJson(null, {
                onEachFeature: geo_json_3e2b8cc6a8a7184f73f012a76b321db1_onEachFeature,
            
                style: geo_json_3e2b8cc6a8a7184f73f012a76b321db1_styler,
            ...{
}
        });

        function geo_json_3e2b8cc6a8a7184f73f012a76b321db1_add (data) {
            geo_json_3e2b8cc6a8a7184f73f012a76b321db1
                .addData(data);
        }
            geo_json_3e2b8cc6a8a7184f73f012a76b321db1_add({"features": [{"geometry": {"coordinates": [[-79.440369, 43.902767], [-79.440836, 43.905496], [-79.445549, 43.907563], [-79.446548, 43.911482], [-79.448259, 43.913919], [-79.451679, 43.91464], [-79.455704, 43.915314], [-79.459875, 43.914365], [-79.461059, 43.913696], [-79.459624, 43.911194], [-79.45621, 43.909644], [-79.453441, 43.909727], [-79.452108, 43.907121], [-79.454539, 43.906133], [-79.457498, 43.905471], [-79.460531, 43.904807], [-79.465812, 43.903649], [-79.466222, 43.904196], [-79.467586, 43.906514], [-79.468054, 43.909855], [-79.469936, 43.913895]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_3e2b8cc6a8a7184f73f012a76b321db1.bindTooltip(
                `<div>
                     442 RICHMOND HILL SS VIA GAMBLE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_3e2b8cc6a8a7184f73f012a76b321db1.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_0128e3e88545843a85a711757792e7a3_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_0128e3e88545843a85a711757792e7a3_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_0128e3e88545843a85a711757792e7a3 = L.geoJson(null, {
                onEachFeature: geo_json_0128e3e88545843a85a711757792e7a3_onEachFeature,
            
                style: geo_json_0128e3e88545843a85a711757792e7a3_styler,
            ...{
}
        });

        function geo_json_0128e3e88545843a85a711757792e7a3_add (data) {
            geo_json_0128e3e88545843a85a711757792e7a3
                .addData(data);
        }
            geo_json_0128e3e88545843a85a711757792e7a3_add({"features": [{"geometry": {"coordinates": [[-79.441694, 43.894956], [-79.439046, 43.895895], [-79.440335, 43.899402], [-79.441911, 43.899041], [-79.44295, 43.895054], [-79.445329, 43.893989], [-79.448492, 43.892878], [-79.45406, 43.891661], [-79.455428, 43.89333], [-79.457429, 43.895149], [-79.461778, 43.896238], [-79.466174, 43.895388], [-79.468936, 43.894405], [-79.466513, 43.884222], [-79.462686, 43.884967], [-79.460766, 43.885405], [-79.457958, 43.886002], [-79.45251, 43.887152], [-79.451736, 43.88496], [-79.450972, 43.881431], [-79.45457, 43.880639], [-79.456523, 43.88098], [-79.458798, 43.880694], [-79.462375, 43.879029], [-79.462131, 43.877554], [-79.460569, 43.876119], [-79.459573, 43.874179], [-79.456629, 43.874836], [-79.454703, 43.875247], [-79.451593, 43.875865], [-79.450897, 43.874279], [-79.449496, 43.869987], [-79.44905, 43.86894], [-79.448577, 43.867894], [-79.445925, 43.867271], [-79.447055, 43.86483], [-79.446477, 43.862705], [-79.445821, 43.860887], [-79.445164, 43.858318], [-79.440848, 43.858897], [-79.439657, 43.857251], [-79.438977, 43.855631], [-79.440445, 43.853094], [-79.44583, 43.852181], [-79.445608, 43.85071], [-79.44454, 43.848033], [-79.443838, 43.845944], [-79.440723, 43.846405], [-79.438173, 43.846739], [-79.438166, 43.845127], [-79.43757, 43.84312], [-79.437037, 43.841202], [-79.437065, 43.839268], [-79.436466, 43.838049], [-79.430101, 43.8391], [-79.42546, 43.839813]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_0128e3e88545843a85a711757792e7a3.bindTooltip(
                `<div>
                     443 LANGSTAFF SS VIA SHAFTSBURY
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_0128e3e88545843a85a711757792e7a3.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_1ce8d676ed4c1c282075387865195ddb_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_1ce8d676ed4c1c282075387865195ddb_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_1ce8d676ed4c1c282075387865195ddb = L.geoJson(null, {
                onEachFeature: geo_json_1ce8d676ed4c1c282075387865195ddb_onEachFeature,
            
                style: geo_json_1ce8d676ed4c1c282075387865195ddb_styler,
            ...{
}
        });

        function geo_json_1ce8d676ed4c1c282075387865195ddb_add (data) {
            geo_json_1ce8d676ed4c1c282075387865195ddb
                .addData(data);
        }
            geo_json_1ce8d676ed4c1c282075387865195ddb_add({"features": [{"geometry": {"coordinates": [[-79.42546, 43.839813], [-79.430269, 43.839232], [-79.436214, 43.837963], [-79.43694, 43.83945], [-79.436835, 43.840946], [-79.437352, 43.842926], [-79.438092, 43.844814], [-79.438091, 43.84692], [-79.440083, 43.84663], [-79.443551, 43.845938], [-79.444146, 43.847395], [-79.445317, 43.850283], [-79.445604, 43.852316], [-79.440679, 43.852971], [-79.438975, 43.854824], [-79.439376, 43.857064], [-79.440563, 43.858848], [-79.444738, 43.858199], [-79.445533, 43.860459], [-79.446245, 43.86243], [-79.446993, 43.864496], [-79.445548, 43.86715], [-79.448628, 43.868421], [-79.449247, 43.869988], [-79.45066, 43.873738], [-79.45123, 43.875799], [-79.454363, 43.875387], [-79.456274, 43.874972], [-79.460058, 43.874171], [-79.460349, 43.875901], [-79.461911, 43.877568], [-79.462097, 43.878953], [-79.459067, 43.880494], [-79.456888, 43.880906], [-79.453652, 43.880399], [-79.450985, 43.881129], [-79.451475, 43.88466], [-79.452059, 43.886842], [-79.457556, 43.886255], [-79.460382, 43.885606], [-79.463536, 43.884979], [-79.466976, 43.884296], [-79.468179, 43.888451], [-79.469466, 43.893874], [-79.466186, 43.895251], [-79.462229, 43.896075], [-79.457803, 43.895321], [-79.455697, 43.893368], [-79.454339, 43.891684], [-79.448027, 43.892868], [-79.445538, 43.893705], [-79.443054, 43.894677], [-79.441694, 43.894956]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_1ce8d676ed4c1c282075387865195ddb.bindTooltip(
                `<div>
                     443 LANGSTAFF SS VIA SHAFTSBURY
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_1ce8d676ed4c1c282075387865195ddb.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_4a474e1d112c6c9bc997606a948dfd31_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_4a474e1d112c6c9bc997606a948dfd31_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_4a474e1d112c6c9bc997606a948dfd31 = L.geoJson(null, {
                onEachFeature: geo_json_4a474e1d112c6c9bc997606a948dfd31_onEachFeature,
            
                style: geo_json_4a474e1d112c6c9bc997606a948dfd31_styler,
            ...{
}
        });

        function geo_json_4a474e1d112c6c9bc997606a948dfd31_add (data) {
            geo_json_4a474e1d112c6c9bc997606a948dfd31
                .addData(data);
        }
            geo_json_4a474e1d112c6c9bc997606a948dfd31_add({"features": [{"geometry": {"coordinates": [[-79.384056, 43.840264], [-79.38645, 43.839276], [-79.388521, 43.838226], [-79.390983, 43.838584], [-79.391724, 43.839852], [-79.391539, 43.84196], [-79.392126, 43.843585], [-79.393014, 43.845719], [-79.396029, 43.845538], [-79.398935, 43.845645], [-79.399896, 43.847533], [-79.400872, 43.849594], [-79.401417, 43.852846], [-79.40138, 43.854758], [-79.401257, 43.856093], [-79.39877, 43.857242], [-79.395589, 43.85871], [-79.40249, 43.859024], [-79.410691, 43.856002], [-79.410168, 43.853831], [-79.409795, 43.852127], [-79.408834, 43.848219], [-79.408127, 43.845365], [-79.409187, 43.844984], [-79.411308, 43.844197], [-79.414573, 43.843036], [-79.415174, 43.844784], [-79.415687, 43.846648], [-79.416167, 43.848537], [-79.418178, 43.849554], [-79.42057, 43.849247], [-79.423272, 43.8491], [-79.426292, 43.848761], [-79.426164, 43.847594], [-79.424851, 43.84581], [-79.424281, 43.843877], [-79.422957, 43.841393], [-79.421021, 43.839908], [-79.42546, 43.839813], [-79.430269, 43.839232], [-79.436214, 43.837963], [-79.43694, 43.83945]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_4a474e1d112c6c9bc997606a948dfd31.bindTooltip(
                `<div>
                     444 LANGSTAFF SS VIA VALLEYMEDE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_4a474e1d112c6c9bc997606a948dfd31.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_ca3f1bb229ca7bea0ac5d7a8120fdc99_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_ca3f1bb229ca7bea0ac5d7a8120fdc99_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_ca3f1bb229ca7bea0ac5d7a8120fdc99 = L.geoJson(null, {
                onEachFeature: geo_json_ca3f1bb229ca7bea0ac5d7a8120fdc99_onEachFeature,
            
                style: geo_json_ca3f1bb229ca7bea0ac5d7a8120fdc99_styler,
            ...{
}
        });

        function geo_json_ca3f1bb229ca7bea0ac5d7a8120fdc99_add (data) {
            geo_json_ca3f1bb229ca7bea0ac5d7a8120fdc99
                .addData(data);
        }
            geo_json_ca3f1bb229ca7bea0ac5d7a8120fdc99_add({"features": [{"geometry": {"coordinates": [[-79.437065, 43.839268], [-79.436466, 43.838049], [-79.430101, 43.8391], [-79.422889, 43.841795], [-79.424129, 43.843914], [-79.42455, 43.845371], [-79.426378, 43.848433], [-79.423769, 43.849013], [-79.421219, 43.849045], [-79.416391, 43.849001], [-79.415382, 43.844961], [-79.411367, 43.843923], [-79.40843, 43.847824], [-79.409373, 43.851765], [-79.409951, 43.854023], [-79.410517, 43.856027], [-79.410794, 43.857606], [-79.403154, 43.858649], [-79.396414, 43.860144], [-79.395704, 43.858952], [-79.398645, 43.857362], [-79.401239, 43.856403], [-79.401484, 43.854963], [-79.401592, 43.853404], [-79.401193, 43.849848], [-79.400187, 43.847745], [-79.399216, 43.8458], [-79.396302, 43.845397], [-79.393373, 43.845747], [-79.392381, 43.844199], [-79.392012, 43.842615], [-79.391904, 43.840135], [-79.388262, 43.838129], [-79.386521, 43.838841], [-79.383881, 43.840137]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_ca3f1bb229ca7bea0ac5d7a8120fdc99.bindTooltip(
                `<div>
                     444 LANGSTAFF SS VIA VALLEYMEDE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_ca3f1bb229ca7bea0ac5d7a8120fdc99.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_7c7de80e2091163f68922d54a6ffbfb6_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_7c7de80e2091163f68922d54a6ffbfb6_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_7c7de80e2091163f68922d54a6ffbfb6 = L.geoJson(null, {
                onEachFeature: geo_json_7c7de80e2091163f68922d54a6ffbfb6_onEachFeature,
            
                style: geo_json_7c7de80e2091163f68922d54a6ffbfb6_styler,
            ...{
}
        });

        function geo_json_7c7de80e2091163f68922d54a6ffbfb6_add (data) {
            geo_json_7c7de80e2091163f68922d54a6ffbfb6
                .addData(data);
        }
            geo_json_7c7de80e2091163f68922d54a6ffbfb6_add({"features": [{"geometry": {"coordinates": [[-79.376713, 43.83482], [-79.381612, 43.839414], [-79.384056, 43.840264], [-79.38645, 43.839276], [-79.388521, 43.838226], [-79.390983, 43.838584], [-79.391724, 43.839852], [-79.391539, 43.84196], [-79.392126, 43.843585], [-79.393014, 43.845719], [-79.396029, 43.845538], [-79.398935, 43.845645], [-79.399896, 43.847533], [-79.400872, 43.849594], [-79.401417, 43.852846], [-79.40138, 43.854758], [-79.401257, 43.856093], [-79.39877, 43.857242], [-79.395589, 43.85871], [-79.395887, 43.860189], [-79.398737, 43.863827], [-79.40031, 43.866207], [-79.40094, 43.86966], [-79.401671, 43.871023], [-79.40352, 43.87278], [-79.404466, 43.874286], [-79.40598, 43.87612], [-79.411998, 43.876305], [-79.415047, 43.876239], [-79.416725, 43.875857], [-79.420892, 43.874917], [-79.425623, 43.877612], [-79.426708, 43.879746], [-79.429176, 43.882201], [-79.430758, 43.884104], [-79.431853, 43.886765], [-79.432069, 43.889079], [-79.431345, 43.891294], [-79.436046, 43.890895], [-79.4412, 43.889828], [-79.442098, 43.894543]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_7c7de80e2091163f68922d54a6ffbfb6.bindTooltip(
                `<div>
                     445 ST ROBERT SS VIA SPADINA
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_7c7de80e2091163f68922d54a6ffbfb6.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_95e17c135d02f0a9391e39dfb2896d54_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_95e17c135d02f0a9391e39dfb2896d54_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_95e17c135d02f0a9391e39dfb2896d54 = L.geoJson(null, {
                onEachFeature: geo_json_95e17c135d02f0a9391e39dfb2896d54_onEachFeature,
            
                style: geo_json_95e17c135d02f0a9391e39dfb2896d54_styler,
            ...{
}
        });

        function geo_json_95e17c135d02f0a9391e39dfb2896d54_add (data) {
            geo_json_95e17c135d02f0a9391e39dfb2896d54
                .addData(data);
        }
            geo_json_95e17c135d02f0a9391e39dfb2896d54_add({"features": [{"geometry": {"coordinates": [[-79.461653, 43.861501], [-79.45862, 43.862576], [-79.454957, 43.864316], [-79.457318, 43.866113], [-79.462371, 43.866089], [-79.465521, 43.873114], [-79.468294, 43.872914], [-79.470765, 43.872512], [-79.471879, 43.874742], [-79.474439, 43.875903], [-79.478994, 43.87698], [-79.482479, 43.875567], [-79.484685, 43.877361], [-79.485946, 43.879945], [-79.481903, 43.880988], [-79.470018, 43.883454], [-79.468179, 43.888451], [-79.469466, 43.893874], [-79.466186, 43.895251]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_95e17c135d02f0a9391e39dfb2896d54.bindTooltip(
                `<div>
                     446 ST THERESA SS VIA MCCALLUM
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_95e17c135d02f0a9391e39dfb2896d54.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_f03cc6942439bc634d2a5c49f59c6659_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_f03cc6942439bc634d2a5c49f59c6659_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_f03cc6942439bc634d2a5c49f59c6659 = L.geoJson(null, {
                onEachFeature: geo_json_f03cc6942439bc634d2a5c49f59c6659_onEachFeature,
            
                style: geo_json_f03cc6942439bc634d2a5c49f59c6659_styler,
            ...{
}
        });

        function geo_json_f03cc6942439bc634d2a5c49f59c6659_add (data) {
            geo_json_f03cc6942439bc634d2a5c49f59c6659
                .addData(data);
        }
            geo_json_f03cc6942439bc634d2a5c49f59c6659_add({"features": [{"geometry": {"coordinates": [[-79.466186, 43.895251], [-79.463882, 43.894823], [-79.461831, 43.892813], [-79.459894, 43.890199], [-79.460382, 43.885606], [-79.463536, 43.884979], [-79.466976, 43.884296], [-79.473689, 43.882915], [-79.481466, 43.880467], [-79.48102, 43.879229], [-79.482479, 43.875567], [-79.484685, 43.877361], [-79.485946, 43.879945], [-79.481903, 43.880988], [-79.481466, 43.880467], [-79.48102, 43.879229], [-79.479559, 43.877269], [-79.475616, 43.876017], [-79.472591, 43.875122], [-79.471082, 43.872537], [-79.46811, 43.872787], [-79.465494, 43.872984], [-79.463053, 43.866649], [-79.457965, 43.866675], [-79.457414, 43.866032], [-79.456345, 43.864769], [-79.455725, 43.863773], [-79.458043, 43.863184], [-79.459836, 43.862155], [-79.461103, 43.861875]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_f03cc6942439bc634d2a5c49f59c6659.bindTooltip(
                `<div>
                     446 ST THERESA SS VIA MCCALLUM
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_f03cc6942439bc634d2a5c49f59c6659.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_a18aafc603ee1cd7f9837425ac70ee47_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_a18aafc603ee1cd7f9837425ac70ee47_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_a18aafc603ee1cd7f9837425ac70ee47 = L.geoJson(null, {
                onEachFeature: geo_json_a18aafc603ee1cd7f9837425ac70ee47_onEachFeature,
            
                style: geo_json_a18aafc603ee1cd7f9837425ac70ee47_styler,
            ...{
}
        });

        function geo_json_a18aafc603ee1cd7f9837425ac70ee47_add (data) {
            geo_json_a18aafc603ee1cd7f9837425ac70ee47
                .addData(data);
        }
            geo_json_a18aafc603ee1cd7f9837425ac70ee47_add({"features": [{"geometry": {"coordinates": [[-79.442272, 43.915191], [-79.43706, 43.916375], [-79.43481, 43.916803], [-79.433112, 43.915613], [-79.43276, 43.913428], [-79.435952, 43.913066], [-79.441366, 43.915537], [-79.446681, 43.914222], [-79.446945, 43.911874], [-79.444166, 43.908161], [-79.440081, 43.90908], [-79.434518, 43.909347], [-79.432869, 43.908081], [-79.432208, 43.906514], [-79.43467, 43.905058], [-79.436588, 43.904813], [-79.440859, 43.905785], [-79.440169, 43.901903], [-79.438098, 43.899597], [-79.434893, 43.89975], [-79.431873, 43.899043], [-79.433284, 43.895475], [-79.438828, 43.895451], [-79.441622, 43.89517], [-79.445329, 43.893989], [-79.448492, 43.892878], [-79.45406, 43.891661], [-79.455428, 43.89333], [-79.457429, 43.895149], [-79.461778, 43.896238], [-79.466174, 43.895388]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_a18aafc603ee1cd7f9837425ac70ee47.bindTooltip(
                `<div>
                     447 ST THERESA SS VIA JEFFERSON FOREST
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_a18aafc603ee1cd7f9837425ac70ee47.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_65ff084dcccb8a28101d198ed7c43b5a_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_65ff084dcccb8a28101d198ed7c43b5a_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_65ff084dcccb8a28101d198ed7c43b5a = L.geoJson(null, {
                onEachFeature: geo_json_65ff084dcccb8a28101d198ed7c43b5a_onEachFeature,
            
                style: geo_json_65ff084dcccb8a28101d198ed7c43b5a_styler,
            ...{
}
        });

        function geo_json_65ff084dcccb8a28101d198ed7c43b5a_add (data) {
            geo_json_65ff084dcccb8a28101d198ed7c43b5a
                .addData(data);
        }
            geo_json_65ff084dcccb8a28101d198ed7c43b5a_add({"features": [{"geometry": {"coordinates": [[-79.466186, 43.895251], [-79.462229, 43.896075], [-79.457803, 43.895321], [-79.455697, 43.893368], [-79.454339, 43.891684], [-79.445538, 43.893705], [-79.443054, 43.894677], [-79.441694, 43.894956], [-79.439307, 43.89525], [-79.433248, 43.895406], [-79.431747, 43.898559], [-79.435002, 43.899819], [-79.439232, 43.899601], [-79.440369, 43.902767], [-79.440836, 43.905496], [-79.43702, 43.904954], [-79.434867, 43.904903], [-79.432126, 43.906044], [-79.432716, 43.908117], [-79.43462, 43.909926], [-79.439948, 43.909209], [-79.446548, 43.911482], [-79.447089, 43.913846], [-79.442272, 43.915191], [-79.43706, 43.916375], [-79.43481, 43.916803], [-79.433112, 43.915613], [-79.43276, 43.913428], [-79.435952, 43.913066], [-79.441366, 43.915537]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_65ff084dcccb8a28101d198ed7c43b5a.bindTooltip(
                `<div>
                     447 ST THERESA SS VIA JEFFERSON FOREST
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_65ff084dcccb8a28101d198ed7c43b5a.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_b5f263665b3a1a75816559b6cce5c032_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_b5f263665b3a1a75816559b6cce5c032_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_b5f263665b3a1a75816559b6cce5c032 = L.geoJson(null, {
                onEachFeature: geo_json_b5f263665b3a1a75816559b6cce5c032_onEachFeature,
            
                style: geo_json_b5f263665b3a1a75816559b6cce5c032_styler,
            ...{
}
        });

        function geo_json_b5f263665b3a1a75816559b6cce5c032_add (data) {
            geo_json_b5f263665b3a1a75816559b6cce5c032
                .addData(data);
        }
            geo_json_b5f263665b3a1a75816559b6cce5c032_add({"features": [{"geometry": {"coordinates": [[-79.381612, 43.839414], [-79.384056, 43.840264], [-79.38645, 43.839276], [-79.388521, 43.838226], [-79.390983, 43.838584], [-79.391724, 43.839852], [-79.391539, 43.84196], [-79.392126, 43.843585], [-79.393014, 43.845719], [-79.396029, 43.845538], [-79.398935, 43.845645], [-79.399896, 43.847533], [-79.400872, 43.849594], [-79.401417, 43.852846], [-79.40138, 43.854758], [-79.401257, 43.856093], [-79.39877, 43.857242], [-79.395589, 43.85871], [-79.395887, 43.860189], [-79.398737, 43.863827], [-79.40031, 43.866207], [-79.40094, 43.86966], [-79.401671, 43.871023], [-79.40352, 43.87278], [-79.404466, 43.874286], [-79.40598, 43.87612], [-79.410404, 43.877656], [-79.407608, 43.878537], [-79.408032, 43.881204], [-79.411179, 43.880998], [-79.412728, 43.88067], [-79.415555, 43.880054], [-79.421499, 43.878696], [-79.426708, 43.879746], [-79.429176, 43.882201], [-79.430758, 43.884104], [-79.431853, 43.886765], [-79.432069, 43.889079], [-79.431345, 43.891294], [-79.436046, 43.890895], [-79.438204, 43.890483], [-79.4412, 43.889828], [-79.441423, 43.890207], [-79.44235, 43.894633], [-79.441694, 43.894956], [-79.439046, 43.895895], [-79.4393, 43.899319], [-79.440369, 43.902767]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_b5f263665b3a1a75816559b6cce5c032.bindTooltip(
                `<div>
                     448 RICHMOND HILL SS VIA VALLEYMEDE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_b5f263665b3a1a75816559b6cce5c032.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_03fd0c48cd29f794fc833e538c52860e_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_03fd0c48cd29f794fc833e538c52860e_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_03fd0c48cd29f794fc833e538c52860e = L.geoJson(null, {
                onEachFeature: geo_json_03fd0c48cd29f794fc833e538c52860e_onEachFeature,
            
                style: geo_json_03fd0c48cd29f794fc833e538c52860e_styler,
            ...{
}
        });

        function geo_json_03fd0c48cd29f794fc833e538c52860e_add (data) {
            geo_json_03fd0c48cd29f794fc833e538c52860e
                .addData(data);
        }
            geo_json_03fd0c48cd29f794fc833e538c52860e_add({"features": [{"geometry": {"coordinates": [[-79.440169, 43.901903], [-79.439356, 43.896475], [-79.439173, 43.895565], [-79.441622, 43.89517], [-79.438591, 43.890121], [-79.435962, 43.890746], [-79.4315, 43.891677], [-79.43229, 43.88932], [-79.432011, 43.88674], [-79.430865, 43.883931], [-79.429694, 43.882435], [-79.426724, 43.879554], [-79.421787, 43.878546], [-79.416635, 43.87967], [-79.412937, 43.880513], [-79.408304, 43.881187], [-79.407255, 43.87882], [-79.406692, 43.877228], [-79.410471, 43.877827], [-79.407608, 43.878537], [-79.406692, 43.877228], [-79.404697, 43.874521], [-79.402128, 43.871358], [-79.401045, 43.869392], [-79.400527, 43.866438], [-79.399034, 43.863944], [-79.396246, 43.860519], [-79.395704, 43.858952], [-79.398645, 43.857362], [-79.401239, 43.856403], [-79.401484, 43.854963], [-79.401592, 43.853404], [-79.401193, 43.849848], [-79.400187, 43.847745], [-79.399216, 43.8458], [-79.396302, 43.845397], [-79.393373, 43.845747], [-79.392381, 43.844199], [-79.392012, 43.842615], [-79.391904, 43.840135], [-79.391533, 43.838787], [-79.388262, 43.838129], [-79.386521, 43.838841], [-79.383881, 43.840137], [-79.381461, 43.841807]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_03fd0c48cd29f794fc833e538c52860e.bindTooltip(
                `<div>
                     448 RICHMOND HILL SS VIA VALLEYMEDE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_03fd0c48cd29f794fc833e538c52860e.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_28e92bf44f6419cfa705f1f76fd9a801_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_28e92bf44f6419cfa705f1f76fd9a801_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_28e92bf44f6419cfa705f1f76fd9a801 = L.geoJson(null, {
                onEachFeature: geo_json_28e92bf44f6419cfa705f1f76fd9a801_onEachFeature,
            
                style: geo_json_28e92bf44f6419cfa705f1f76fd9a801_styler,
            ...{
}
        });

        function geo_json_28e92bf44f6419cfa705f1f76fd9a801_add (data) {
            geo_json_28e92bf44f6419cfa705f1f76fd9a801
                .addData(data);
        }
            geo_json_28e92bf44f6419cfa705f1f76fd9a801_add({"features": [{"geometry": {"coordinates": [[-79.366976, 43.884408], [-79.366257, 43.881318], [-79.365167, 43.876989], [-79.368041, 43.876536], [-79.371399, 43.876124], [-79.37251, 43.87885], [-79.37246, 43.88218], [-79.385776, 43.882037], [-79.391179, 43.880703], [-79.392321, 43.885693], [-79.393474, 43.889722], [-79.394446, 43.893655], [-79.394941, 43.895489], [-79.395602, 43.898378], [-79.396114, 43.90054], [-79.398484, 43.902467]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_28e92bf44f6419cfa705f1f76fd9a801.bindTooltip(
                `<div>
                     449 RICHMOND GREEN SS VIA HILLMOUNT
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_28e92bf44f6419cfa705f1f76fd9a801.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_e3d9980a443355883cbd98dc5feb2a3c_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_e3d9980a443355883cbd98dc5feb2a3c_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_e3d9980a443355883cbd98dc5feb2a3c = L.geoJson(null, {
                onEachFeature: geo_json_e3d9980a443355883cbd98dc5feb2a3c_onEachFeature,
            
                style: geo_json_e3d9980a443355883cbd98dc5feb2a3c_styler,
            ...{
}
        });

        function geo_json_e3d9980a443355883cbd98dc5feb2a3c_add (data) {
            geo_json_e3d9980a443355883cbd98dc5feb2a3c
                .addData(data);
        }
            geo_json_e3d9980a443355883cbd98dc5feb2a3c_add({"features": [{"geometry": {"coordinates": [[-79.398484, 43.902467], [-79.396565, 43.900932], [-79.396041, 43.898855], [-79.395299, 43.895963], [-79.394872, 43.893986], [-79.393927, 43.890158], [-79.393391, 43.888245], [-79.392934, 43.886649], [-79.386694, 43.881611], [-79.373531, 43.884489], [-79.373012, 43.883873], [-79.372647, 43.879046], [-79.368658, 43.876342], [-79.365701, 43.876642], [-79.365843, 43.880997], [-79.366999, 43.885748]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_e3d9980a443355883cbd98dc5feb2a3c.bindTooltip(
                `<div>
                     449 RICHMOND GREEN SS VIA HILLMOUNT
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_e3d9980a443355883cbd98dc5feb2a3c.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_1e9d757b1026d18b2d0faa7dc2bcdf8c_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_1e9d757b1026d18b2d0faa7dc2bcdf8c_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_1e9d757b1026d18b2d0faa7dc2bcdf8c = L.geoJson(null, {
                onEachFeature: geo_json_1e9d757b1026d18b2d0faa7dc2bcdf8c_onEachFeature,
            
                style: geo_json_1e9d757b1026d18b2d0faa7dc2bcdf8c_styler,
            ...{
}
        });

        function geo_json_1e9d757b1026d18b2d0faa7dc2bcdf8c_add (data) {
            geo_json_1e9d757b1026d18b2d0faa7dc2bcdf8c
                .addData(data);
        }
            geo_json_1e9d757b1026d18b2d0faa7dc2bcdf8c_add({"features": [{"geometry": {"coordinates": [[-79.449992, 43.922505], [-79.455375, 43.921461], [-79.45624, 43.921204], [-79.460666, 43.920277], [-79.466628, 43.918963], [-79.470681, 43.91809], [-79.474282, 43.91729], [-79.472352, 43.91349], [-79.469747, 43.913809], [-79.468708, 43.914036], [-79.464204, 43.913937], [-79.456688, 43.914955], [-79.451411, 43.914303], [-79.447832, 43.913892], [-79.446945, 43.911874], [-79.446084, 43.908107], [-79.448952, 43.907328], [-79.451476, 43.906838], [-79.452194, 43.907695], [-79.452893, 43.909438], [-79.455718, 43.909866], [-79.459239, 43.911111], [-79.460927, 43.913656], [-79.462487, 43.914093], [-79.468867, 43.914125], [-79.468202, 43.910365], [-79.467778, 43.906634], [-79.466312, 43.903792], [-79.466186, 43.895251]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_1e9d757b1026d18b2d0faa7dc2bcdf8c.bindTooltip(
                `<div>
                     450 ST THERESA SS VIA TOWER HILL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_1e9d757b1026d18b2d0faa7dc2bcdf8c.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_ed660feecb14b27eb416bf0806b1c3c4_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_ed660feecb14b27eb416bf0806b1c3c4_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_ed660feecb14b27eb416bf0806b1c3c4 = L.geoJson(null, {
                onEachFeature: geo_json_ed660feecb14b27eb416bf0806b1c3c4_onEachFeature,
            
                style: geo_json_ed660feecb14b27eb416bf0806b1c3c4_styler,
            ...{
}
        });

        function geo_json_ed660feecb14b27eb416bf0806b1c3c4_add (data) {
            geo_json_ed660feecb14b27eb416bf0806b1c3c4
                .addData(data);
        }
            geo_json_ed660feecb14b27eb416bf0806b1c3c4_add({"features": [{"geometry": {"coordinates": [[-79.466174, 43.895388], [-79.468936, 43.894405], [-79.471589, 43.902252], [-79.466222, 43.904196], [-79.467586, 43.906514], [-79.468054, 43.909855], [-79.468708, 43.914036], [-79.464204, 43.913937], [-79.456688, 43.914955], [-79.451411, 43.914303], [-79.447832, 43.913892], [-79.446945, 43.911874], [-79.446084, 43.908107], [-79.448952, 43.907328], [-79.451476, 43.906838], [-79.452194, 43.907695], [-79.452893, 43.909438], [-79.455718, 43.909866], [-79.459239, 43.911111], [-79.460927, 43.913656], [-79.462487, 43.914093], [-79.468867, 43.914125], [-79.469936, 43.913895], [-79.474154, 43.913424], [-79.475123, 43.916746], [-79.471131, 43.917816], [-79.46717, 43.91865], [-79.461011, 43.920002], [-79.456222, 43.921096], [-79.449648, 43.922405]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_ed660feecb14b27eb416bf0806b1c3c4.bindTooltip(
                `<div>
                     450 ST THERESA SS VIA TOWER HILL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_ed660feecb14b27eb416bf0806b1c3c4.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_1c613fe54073983768df1abeb16d0c36_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_1c613fe54073983768df1abeb16d0c36_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_1c613fe54073983768df1abeb16d0c36 = L.geoJson(null, {
                onEachFeature: geo_json_1c613fe54073983768df1abeb16d0c36_onEachFeature,
            
                style: geo_json_1c613fe54073983768df1abeb16d0c36_styler,
            ...{
}
        });

        function geo_json_1c613fe54073983768df1abeb16d0c36_add (data) {
            geo_json_1c613fe54073983768df1abeb16d0c36
                .addData(data);
        }
            geo_json_1c613fe54073983768df1abeb16d0c36_add({"features": [{"geometry": {"coordinates": [[-79.375154, 43.903251], [-79.372092, 43.903953], [-79.37074, 43.899619], [-79.367871, 43.896972], [-79.366251, 43.894185], [-79.36526, 43.89187], [-79.362932, 43.889548], [-79.361844, 43.887451], [-79.366788, 43.886178], [-79.367353, 43.887033], [-79.368629, 43.888654], [-79.368384, 43.89068], [-79.368918, 43.89311], [-79.371269, 43.896769], [-79.372906, 43.896763], [-79.376758, 43.896583], [-79.378487, 43.896996], [-79.377247, 43.899746], [-79.377272, 43.901278], [-79.391956, 43.899651], [-79.395253, 43.898848], [-79.396114, 43.90054], [-79.398484, 43.902467]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_1c613fe54073983768df1abeb16d0c36.bindTooltip(
                `<div>
                     452 RICHMOND GREEN SS VIA HAZELTON
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_1c613fe54073983768df1abeb16d0c36.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_793a0cdbdca5ad6443e56cff51733d60_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_793a0cdbdca5ad6443e56cff51733d60_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_793a0cdbdca5ad6443e56cff51733d60 = L.geoJson(null, {
                onEachFeature: geo_json_793a0cdbdca5ad6443e56cff51733d60_onEachFeature,
            
                style: geo_json_793a0cdbdca5ad6443e56cff51733d60_styler,
            ...{
}
        });

        function geo_json_793a0cdbdca5ad6443e56cff51733d60_add (data) {
            geo_json_793a0cdbdca5ad6443e56cff51733d60
                .addData(data);
        }
            geo_json_793a0cdbdca5ad6443e56cff51733d60_add({"features": [{"geometry": {"coordinates": [[-79.398484, 43.902467], [-79.396565, 43.900932], [-79.39256, 43.899314], [-79.378282, 43.902493], [-79.375154, 43.903251], [-79.372092, 43.903953], [-79.37074, 43.899619], [-79.367871, 43.896972], [-79.366251, 43.894185], [-79.36526, 43.89187], [-79.362932, 43.889548], [-79.361844, 43.887451], [-79.366788, 43.886178], [-79.367353, 43.887033], [-79.368629, 43.888654], [-79.368384, 43.89068], [-79.368918, 43.89311], [-79.371269, 43.896769], [-79.372906, 43.896763], [-79.376758, 43.896583], [-79.378487, 43.896996], [-79.377247, 43.899746], [-79.377272, 43.901278]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_793a0cdbdca5ad6443e56cff51733d60.bindTooltip(
                `<div>
                     452 RICHMOND GREEN SS VIA HAZELTON
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_793a0cdbdca5ad6443e56cff51733d60.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_541dc4cbb2178e17333cf25da09dac25_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_541dc4cbb2178e17333cf25da09dac25_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_541dc4cbb2178e17333cf25da09dac25 = L.geoJson(null, {
                onEachFeature: geo_json_541dc4cbb2178e17333cf25da09dac25_onEachFeature,
            
                style: geo_json_541dc4cbb2178e17333cf25da09dac25_styler,
            ...{
}
        });

        function geo_json_541dc4cbb2178e17333cf25da09dac25_add (data) {
            geo_json_541dc4cbb2178e17333cf25da09dac25
                .addData(data);
        }
            geo_json_541dc4cbb2178e17333cf25da09dac25_add({"features": [{"geometry": {"coordinates": [[-79.607565, 43.769042], [-79.608515, 43.772903], [-79.609193, 43.775647], [-79.609866, 43.777783], [-79.610555, 43.78081], [-79.610659, 43.783703], [-79.61131, 43.785272], [-79.611916, 43.786659], [-79.613012, 43.789375], [-79.615866, 43.790929], [-79.620413, 43.791815], [-79.621838, 43.791352], [-79.623201, 43.788798], [-79.622442, 43.784712], [-79.618095, 43.784952], [-79.618022, 43.788208]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_541dc4cbb2178e17333cf25da09dac25.bindTooltip(
                `<div>
                     460 HOLY CROSS SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_541dc4cbb2178e17333cf25da09dac25.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_0bdff1937b3124f1bf3358902d57a6db_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_0bdff1937b3124f1bf3358902d57a6db_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_0bdff1937b3124f1bf3358902d57a6db = L.geoJson(null, {
                onEachFeature: geo_json_0bdff1937b3124f1bf3358902d57a6db_onEachFeature,
            
                style: geo_json_0bdff1937b3124f1bf3358902d57a6db_styler,
            ...{
}
        });

        function geo_json_0bdff1937b3124f1bf3358902d57a6db_add (data) {
            geo_json_0bdff1937b3124f1bf3358902d57a6db
                .addData(data);
        }
            geo_json_0bdff1937b3124f1bf3358902d57a6db_add({"features": [{"geometry": {"coordinates": [[-79.62039, 43.793749], [-79.6191, 43.798426], [-79.622507, 43.800516], [-79.62528, 43.800884], [-79.628141, 43.800314], [-79.628762, 43.806205], [-79.628488, 43.806354], [-79.626291, 43.803775], [-79.620491, 43.802309], [-79.61513, 43.800138], [-79.610591, 43.799723], [-79.611533, 43.802427], [-79.610148, 43.804045], [-79.612133, 43.806027], [-79.613689, 43.809169], [-79.615261, 43.811453], [-79.616569, 43.813884], [-79.618076, 43.814864], [-79.620676, 43.814527], [-79.623266, 43.815483], [-79.62513, 43.81722], [-79.625605, 43.819785], [-79.624827, 43.821181], [-79.622131, 43.822577], [-79.620199, 43.822973], [-79.617296, 43.823517], [-79.614259, 43.824148], [-79.611034, 43.825414], [-79.609719, 43.825861], [-79.608323, 43.824053], [-79.607108, 43.821969], [-79.603197, 43.818772], [-79.598943, 43.817264], [-79.595808, 43.817917], [-79.594782, 43.817326]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_0bdff1937b3124f1bf3358902d57a6db.bindTooltip(
                `<div>
                     461 EMILY CARR SS VIA ROYALPARK
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_0bdff1937b3124f1bf3358902d57a6db.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_1f8861f183447c6c0959381b6aeca9cf_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_1f8861f183447c6c0959381b6aeca9cf_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_1f8861f183447c6c0959381b6aeca9cf = L.geoJson(null, {
                onEachFeature: geo_json_1f8861f183447c6c0959381b6aeca9cf_onEachFeature,
            
                style: geo_json_1f8861f183447c6c0959381b6aeca9cf_styler,
            ...{
}
        });

        function geo_json_1f8861f183447c6c0959381b6aeca9cf_add (data) {
            geo_json_1f8861f183447c6c0959381b6aeca9cf
                .addData(data);
        }
            geo_json_1f8861f183447c6c0959381b6aeca9cf_add({"features": [{"geometry": {"coordinates": [[-79.594782, 43.817326], [-79.600164, 43.817235], [-79.606616, 43.821716], [-79.607797, 43.823641], [-79.609092, 43.825939], [-79.610178, 43.825882], [-79.613132, 43.824491], [-79.617759, 43.823545], [-79.621946, 43.822684], [-79.62572, 43.820004], [-79.625334, 43.81734], [-79.62398, 43.815947], [-79.620992, 43.814403], [-79.617851, 43.814666], [-79.61664, 43.813628], [-79.615936, 43.812224], [-79.613794, 43.808941], [-79.612289, 43.806064], [-79.610266, 43.804155], [-79.611794, 43.802356], [-79.610073, 43.798807], [-79.614801, 43.800123], [-79.618989, 43.802006], [-79.625711, 43.803805], [-79.628443, 43.806424], [-79.627342, 43.800252], [-79.62579, 43.800621], [-79.622089, 43.800231], [-79.619269, 43.798772], [-79.620649, 43.793885]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_1f8861f183447c6c0959381b6aeca9cf.bindTooltip(
                `<div>
                     461 EMILY CARR SS VIA ROYALPARK
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_1f8861f183447c6c0959381b6aeca9cf.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_5746ac45eb0fd8fc0dc6c0b25e4758fb_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_5746ac45eb0fd8fc0dc6c0b25e4758fb_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_5746ac45eb0fd8fc0dc6c0b25e4758fb = L.geoJson(null, {
                onEachFeature: geo_json_5746ac45eb0fd8fc0dc6c0b25e4758fb_onEachFeature,
            
                style: geo_json_5746ac45eb0fd8fc0dc6c0b25e4758fb_styler,
            ...{
}
        });

        function geo_json_5746ac45eb0fd8fc0dc6c0b25e4758fb_add (data) {
            geo_json_5746ac45eb0fd8fc0dc6c0b25e4758fb
                .addData(data);
        }
            geo_json_5746ac45eb0fd8fc0dc6c0b25e4758fb_add({"features": [{"geometry": {"coordinates": [[-79.50783, 43.836238], [-79.508534, 43.839134], [-79.509257, 43.842034], [-79.510168, 43.845448], [-79.511249, 43.850258], [-79.511825, 43.852815], [-79.516385, 43.854123], [-79.520313, 43.853344], [-79.526866, 43.85207], [-79.527243, 43.852505], [-79.52319, 43.858369], [-79.519793, 43.85999], [-79.51437, 43.860881], [-79.514573, 43.864946], [-79.516166, 43.867529], [-79.519899, 43.866917], [-79.524698, 43.86596], [-79.528726, 43.865484], [-79.530141, 43.865214], [-79.534811, 43.863432], [-79.538804, 43.862774], [-79.543344, 43.861699], [-79.546593, 43.859781], [-79.548248, 43.858524], [-79.547419, 43.855994], [-79.544393, 43.85634], [-79.542101, 43.856604], [-79.538592, 43.856953], [-79.537758, 43.853789], [-79.534676, 43.850013], [-79.532337, 43.85072], [-79.531342, 43.848507], [-79.530933, 43.846959], [-79.530493, 43.8439], [-79.530314, 43.842709], [-79.529151, 43.840125], [-79.530693, 43.838937]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_5746ac45eb0fd8fc0dc6c0b25e4758fb.bindTooltip(
                `<div>
                     462 MAPLE SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_5746ac45eb0fd8fc0dc6c0b25e4758fb.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_e33875a34f54a2e023f5d85d87d0a033_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_e33875a34f54a2e023f5d85d87d0a033_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_e33875a34f54a2e023f5d85d87d0a033 = L.geoJson(null, {
                onEachFeature: geo_json_e33875a34f54a2e023f5d85d87d0a033_onEachFeature,
            
                style: geo_json_e33875a34f54a2e023f5d85d87d0a033_styler,
            ...{
}
        });

        function geo_json_e33875a34f54a2e023f5d85d87d0a033_add (data) {
            geo_json_e33875a34f54a2e023f5d85d87d0a033
                .addData(data);
        }
            geo_json_e33875a34f54a2e023f5d85d87d0a033_add({"features": [{"geometry": {"coordinates": [[-79.53126, 43.838741], [-79.52895, 43.840137], [-79.53006, 43.84233], [-79.530307, 43.843611], [-79.530617, 43.846546], [-79.531689, 43.850142], [-79.536186, 43.849826], [-79.537308, 43.853307], [-79.539611, 43.856999], [-79.541733, 43.856733], [-79.544107, 43.856469], [-79.547137, 43.856022], [-79.548354, 43.858275], [-79.546471, 43.85973], [-79.543865, 43.86142], [-79.540371, 43.862437], [-79.535406, 43.862855], [-79.53004, 43.865088], [-79.525093, 43.865753], [-79.520434, 43.866673], [-79.515731, 43.867415], [-79.514639, 43.8644], [-79.51395, 43.861251], [-79.519195, 43.860255], [-79.523087, 43.858739], [-79.526266, 43.851972], [-79.520817, 43.853061], [-79.518076, 43.853615], [-79.512653, 43.854715], [-79.51201, 43.852815], [-79.511528, 43.850705], [-79.510419, 43.845755], [-79.50971, 43.84245], [-79.508947, 43.839456], [-79.508349, 43.836633]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_e33875a34f54a2e023f5d85d87d0a033.bindTooltip(
                `<div>
                     462 MAPLE SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_e33875a34f54a2e023f5d85d87d0a033.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_a99fdd211e80da3e2d38c1212725b6d0_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_a99fdd211e80da3e2d38c1212725b6d0_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_a99fdd211e80da3e2d38c1212725b6d0 = L.geoJson(null, {
                onEachFeature: geo_json_a99fdd211e80da3e2d38c1212725b6d0_onEachFeature,
            
                style: geo_json_a99fdd211e80da3e2d38c1212725b6d0_styler,
            ...{
}
        });

        function geo_json_a99fdd211e80da3e2d38c1212725b6d0_add (data) {
            geo_json_a99fdd211e80da3e2d38c1212725b6d0
                .addData(data);
        }
            geo_json_a99fdd211e80da3e2d38c1212725b6d0_add({"features": [{"geometry": {"coordinates": [[-79.537758, 43.853789], [-79.538992, 43.853374], [-79.540619, 43.853037], [-79.543103, 43.852544], [-79.546568, 43.853325], [-79.547205, 43.855852], [-79.548354, 43.858275], [-79.546471, 43.85973], [-79.543865, 43.86142], [-79.540371, 43.862437], [-79.535406, 43.862855], [-79.53004, 43.865088], [-79.525093, 43.865753], [-79.520434, 43.866673], [-79.515731, 43.867415], [-79.514639, 43.8644], [-79.51395, 43.861251], [-79.519195, 43.860255]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_a99fdd211e80da3e2d38c1212725b6d0.bindTooltip(
                `<div>
                     464 ST JOAN OF ARC SS VIA AMERICA
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_a99fdd211e80da3e2d38c1212725b6d0.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_1a4911cb7ff4eac78681cbdfd14369ec_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_1a4911cb7ff4eac78681cbdfd14369ec_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_1a4911cb7ff4eac78681cbdfd14369ec = L.geoJson(null, {
                onEachFeature: geo_json_1a4911cb7ff4eac78681cbdfd14369ec_onEachFeature,
            
                style: geo_json_1a4911cb7ff4eac78681cbdfd14369ec_styler,
            ...{
}
        });

        function geo_json_1a4911cb7ff4eac78681cbdfd14369ec_add (data) {
            geo_json_1a4911cb7ff4eac78681cbdfd14369ec
                .addData(data);
        }
            geo_json_1a4911cb7ff4eac78681cbdfd14369ec_add({"features": [{"geometry": {"coordinates": [[-79.519793, 43.85999], [-79.51437, 43.860881], [-79.514573, 43.864946], [-79.515086, 43.867317], [-79.516166, 43.867529], [-79.519899, 43.866917], [-79.524698, 43.86596], [-79.528726, 43.865484], [-79.530141, 43.865214], [-79.534811, 43.863432], [-79.538804, 43.862774], [-79.543344, 43.861699], [-79.546593, 43.859781], [-79.548248, 43.858524], [-79.547419, 43.855994], [-79.546856, 43.854442], [-79.546623, 43.853007], [-79.543736, 43.853193], [-79.540886, 43.852897], [-79.53781, 43.85346]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_1a4911cb7ff4eac78681cbdfd14369ec.bindTooltip(
                `<div>
                     464 ST JOAN OF ARC SS VIA AMERICA
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_1a4911cb7ff4eac78681cbdfd14369ec.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_2dc8ed1115fd9dd2efa071bac76a8851_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_2dc8ed1115fd9dd2efa071bac76a8851_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_2dc8ed1115fd9dd2efa071bac76a8851 = L.geoJson(null, {
                onEachFeature: geo_json_2dc8ed1115fd9dd2efa071bac76a8851_onEachFeature,
            
                style: geo_json_2dc8ed1115fd9dd2efa071bac76a8851_styler,
            ...{
}
        });

        function geo_json_2dc8ed1115fd9dd2efa071bac76a8851_add (data) {
            geo_json_2dc8ed1115fd9dd2efa071bac76a8851
                .addData(data);
        }
            geo_json_2dc8ed1115fd9dd2efa071bac76a8851_add({"features": [{"geometry": {"coordinates": [[-79.510419, 43.845755], [-79.50971, 43.84245], [-79.508947, 43.839456], [-79.508349, 43.836633], [-79.513541, 43.835411], [-79.517067, 43.834686], [-79.521677, 43.833661], [-79.522426, 43.83453], [-79.525604, 43.838385], [-79.52895, 43.840137], [-79.53006, 43.84233], [-79.530307, 43.843611], [-79.530617, 43.846546], [-79.531081, 43.848272], [-79.531689, 43.850142], [-79.527243, 43.852505], [-79.52319, 43.858369], [-79.519793, 43.85999]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_2dc8ed1115fd9dd2efa071bac76a8851.bindTooltip(
                `<div>
                     465 ST JOAN OF ARC SS VIA MELVILLE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_2dc8ed1115fd9dd2efa071bac76a8851.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_087d0ff39709ef5f7b46d9fef57c78d6_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_087d0ff39709ef5f7b46d9fef57c78d6_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_087d0ff39709ef5f7b46d9fef57c78d6 = L.geoJson(null, {
                onEachFeature: geo_json_087d0ff39709ef5f7b46d9fef57c78d6_onEachFeature,
            
                style: geo_json_087d0ff39709ef5f7b46d9fef57c78d6_styler,
            ...{
}
        });

        function geo_json_087d0ff39709ef5f7b46d9fef57c78d6_add (data) {
            geo_json_087d0ff39709ef5f7b46d9fef57c78d6
                .addData(data);
        }
            geo_json_087d0ff39709ef5f7b46d9fef57c78d6_add({"features": [{"geometry": {"coordinates": [[-79.519195, 43.860255], [-79.523087, 43.858739], [-79.527453, 43.852084], [-79.531817, 43.851079], [-79.532006, 43.850405], [-79.531342, 43.848507], [-79.530933, 43.846959], [-79.530493, 43.8439], [-79.530314, 43.842709], [-79.529151, 43.840125], [-79.526286, 43.838482], [-79.522587, 43.834436], [-79.517633, 43.834339], [-79.51401, 43.83509], [-79.508534, 43.839134], [-79.509257, 43.842034], [-79.510168, 43.845448]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_087d0ff39709ef5f7b46d9fef57c78d6.bindTooltip(
                `<div>
                     465 ST JOAN OF ARC SS VIA MELVILLE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_087d0ff39709ef5f7b46d9fef57c78d6.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_ac73705c6a5078732cd0409f802e286c_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_ac73705c6a5078732cd0409f802e286c_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_ac73705c6a5078732cd0409f802e286c = L.geoJson(null, {
                onEachFeature: geo_json_ac73705c6a5078732cd0409f802e286c_onEachFeature,
            
                style: geo_json_ac73705c6a5078732cd0409f802e286c_styler,
            ...{
}
        });

        function geo_json_ac73705c6a5078732cd0409f802e286c_add (data) {
            geo_json_ac73705c6a5078732cd0409f802e286c
                .addData(data);
        }
            geo_json_ac73705c6a5078732cd0409f802e286c_add({"features": [{"geometry": {"coordinates": [[-79.534583, 43.827081], [-79.542212, 43.828887], [-79.55202, 43.826906], [-79.555823, 43.826346], [-79.562378, 43.825296], [-79.562802, 43.825889], [-79.568208, 43.826001], [-79.572977, 43.825477], [-79.576601, 43.825303], [-79.576887, 43.828173], [-79.575726, 43.830603], [-79.572449, 43.830545], [-79.564318, 43.83161], [-79.564474, 43.83343], [-79.564425, 43.835987], [-79.564916, 43.839487], [-79.566347, 43.843264]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_ac73705c6a5078732cd0409f802e286c.bindTooltip(
                `<div>
                     466 TOMMY DOUGLAS SS VIA FOSSIL HILL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_ac73705c6a5078732cd0409f802e286c.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_0cc6fee651336fdc1766ac0aefcc7ab8_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#626469", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_0cc6fee651336fdc1766ac0aefcc7ab8_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_0cc6fee651336fdc1766ac0aefcc7ab8 = L.geoJson(null, {
                onEachFeature: geo_json_0cc6fee651336fdc1766ac0aefcc7ab8_onEachFeature,
            
                style: geo_json_0cc6fee651336fdc1766ac0aefcc7ab8_styler,
            ...{
}
        });

        function geo_json_0cc6fee651336fdc1766ac0aefcc7ab8_add (data) {
            geo_json_0cc6fee651336fdc1766ac0aefcc7ab8
                .addData(data);
        }
            geo_json_0cc6fee651336fdc1766ac0aefcc7ab8_add({"features": [{"geometry": {"coordinates": [[-79.566851, 43.84394], [-79.565253, 43.839861], [-79.564602, 43.836351], [-79.564625, 43.833869], [-79.564432, 43.83151], [-79.567426, 43.830963], [-79.577033, 43.829946], [-79.577069, 43.827814], [-79.576816, 43.825685], [-79.57403, 43.825145], [-79.569677, 43.825737], [-79.564777, 43.826346], [-79.5554, 43.826123], [-79.551817, 43.826688], [-79.539777, 43.829052], [-79.534583, 43.827081]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_0cc6fee651336fdc1766ac0aefcc7ab8.bindTooltip(
                `<div>
                     466 TOMMY DOUGLAS SS VIA FOSSIL HILL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_0cc6fee651336fdc1766ac0aefcc7ab8.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_9be9a32b47b5ba78e0045d89e3eb7f5e_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_9be9a32b47b5ba78e0045d89e3eb7f5e_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_9be9a32b47b5ba78e0045d89e3eb7f5e = L.geoJson(null, {
                onEachFeature: geo_json_9be9a32b47b5ba78e0045d89e3eb7f5e_onEachFeature,
            
                style: geo_json_9be9a32b47b5ba78e0045d89e3eb7f5e_styler,
            ...{
}
        });

        function geo_json_9be9a32b47b5ba78e0045d89e3eb7f5e_add (data) {
            geo_json_9be9a32b47b5ba78e0045d89e3eb7f5e
                .addData(data);
        }
            geo_json_9be9a32b47b5ba78e0045d89e3eb7f5e_add({"features": [{"geometry": {"coordinates": [[-79.566851, 43.84394], [-79.571313, 43.842827], [-79.5722, 43.84433], [-79.5738, 43.846706], [-79.574717, 43.848], [-79.575455, 43.849911], [-79.57611, 43.85128], [-79.574035, 43.851958], [-79.571482, 43.852527], [-79.566892, 43.853979], [-79.563308, 43.855378], [-79.559878, 43.856037], [-79.55611, 43.857198], [-79.554162, 43.857712], [-79.553533, 43.855461], [-79.55324, 43.854185], [-79.552564, 43.850379], [-79.554045, 43.848165], [-79.554392, 43.846448], [-79.556489, 43.84532], [-79.560167, 43.845018], [-79.567416, 43.84362], [-79.571375, 43.842008], [-79.570925, 43.840566], [-79.570187, 43.838877], [-79.569503, 43.837153], [-79.569542, 43.834084], [-79.561871, 43.833704], [-79.559136, 43.834217], [-79.555134, 43.834906], [-79.551036, 43.835676], [-79.550837, 43.833569], [-79.551001, 43.832124], [-79.551598, 43.828105], [-79.539777, 43.829052], [-79.534583, 43.827081]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_9be9a32b47b5ba78e0045d89e3eb7f5e.bindTooltip(
                `<div>
                     467 TOMMY DOUGLAS SS VIA CITYVIEW
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_9be9a32b47b5ba78e0045d89e3eb7f5e.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_39e7b3b62c153dbc95f263f10ed4bf26_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_39e7b3b62c153dbc95f263f10ed4bf26_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_39e7b3b62c153dbc95f263f10ed4bf26 = L.geoJson(null, {
                onEachFeature: geo_json_39e7b3b62c153dbc95f263f10ed4bf26_onEachFeature,
            
                style: geo_json_39e7b3b62c153dbc95f263f10ed4bf26_styler,
            ...{
}
        });

        function geo_json_39e7b3b62c153dbc95f263f10ed4bf26_add (data) {
            geo_json_39e7b3b62c153dbc95f263f10ed4bf26
                .addData(data);
        }
            geo_json_39e7b3b62c153dbc95f263f10ed4bf26_add({"features": [{"geometry": {"coordinates": [[-79.632953, 43.846106], [-79.629056, 43.844324], [-79.625195, 43.840612], [-79.62385, 43.838925], [-79.621639, 43.836305], [-79.617241, 43.832014], [-79.614386, 43.830359], [-79.612229, 43.829158], [-79.609577, 43.826242], [-79.607108, 43.821969], [-79.603197, 43.818772], [-79.595808, 43.817917]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_39e7b3b62c153dbc95f263f10ed4bf26.bindTooltip(
                `<div>
                     468 EMILY CARR SS VIA KLEINBURG
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_39e7b3b62c153dbc95f263f10ed4bf26.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_c35459d358d4caac011c13b31c39c7ba_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_c35459d358d4caac011c13b31c39c7ba_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_c35459d358d4caac011c13b31c39c7ba = L.geoJson(null, {
                onEachFeature: geo_json_c35459d358d4caac011c13b31c39c7ba_onEachFeature,
            
                style: geo_json_c35459d358d4caac011c13b31c39c7ba_styler,
            ...{
}
        });

        function geo_json_c35459d358d4caac011c13b31c39c7ba_add (data) {
            geo_json_c35459d358d4caac011c13b31c39c7ba
                .addData(data);
        }
            geo_json_c35459d358d4caac011c13b31c39c7ba_add({"features": [{"geometry": {"coordinates": [[-79.595246, 43.818276], [-79.600164, 43.817235], [-79.606616, 43.821716], [-79.607797, 43.823641], [-79.609092, 43.825939], [-79.611558, 43.828994], [-79.61349, 43.830191], [-79.616747, 43.83194], [-79.621002, 43.835803], [-79.623732, 43.839065], [-79.625045, 43.840671], [-79.62841, 43.84417], [-79.633289, 43.843592], [-79.632953, 43.846106]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_c35459d358d4caac011c13b31c39c7ba.bindTooltip(
                `<div>
                     468 EMILY CARR SS VIA KLEINBURG
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_c35459d358d4caac011c13b31c39c7ba.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_628ad0b0c8e7c0ee633b1015ae73f4e6_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_628ad0b0c8e7c0ee633b1015ae73f4e6_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_628ad0b0c8e7c0ee633b1015ae73f4e6 = L.geoJson(null, {
                onEachFeature: geo_json_628ad0b0c8e7c0ee633b1015ae73f4e6_onEachFeature,
            
                style: geo_json_628ad0b0c8e7c0ee633b1015ae73f4e6_styler,
            ...{
}
        });

        function geo_json_628ad0b0c8e7c0ee633b1015ae73f4e6_add (data) {
            geo_json_628ad0b0c8e7c0ee633b1015ae73f4e6
                .addData(data);
        }
            geo_json_628ad0b0c8e7c0ee633b1015ae73f4e6_add({"features": [{"geometry": {"coordinates": [[-79.563487, 43.798486], [-79.562859, 43.795873], [-79.572029, 43.797446], [-79.571121, 43.799946], [-79.569566, 43.801072], [-79.567666, 43.802189], [-79.564608, 43.802761], [-79.564433, 43.804764], [-79.558164, 43.806528], [-79.552303, 43.80773], [-79.548641, 43.808343], [-79.537876, 43.811166], [-79.538528, 43.812825], [-79.539272, 43.815061], [-79.539161, 43.816977], [-79.538805, 43.820118], [-79.539041, 43.821646], [-79.536888, 43.823275], [-79.53437, 43.827187]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_628ad0b0c8e7c0ee633b1015ae73f4e6.bindTooltip(
                `<div>
                     469 FATHER BRESSANI SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_628ad0b0c8e7c0ee633b1015ae73f4e6.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_d9df826d16edd9ee59831d43fd6a15fe_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_d9df826d16edd9ee59831d43fd6a15fe_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_d9df826d16edd9ee59831d43fd6a15fe = L.geoJson(null, {
                onEachFeature: geo_json_d9df826d16edd9ee59831d43fd6a15fe_onEachFeature,
            
                style: geo_json_d9df826d16edd9ee59831d43fd6a15fe_styler,
            ...{
}
        });

        function geo_json_d9df826d16edd9ee59831d43fd6a15fe_add (data) {
            geo_json_d9df826d16edd9ee59831d43fd6a15fe
                .addData(data);
        }
            geo_json_d9df826d16edd9ee59831d43fd6a15fe_add({"features": [{"geometry": {"coordinates": [[-79.482479, 43.875567], [-79.484685, 43.877361], [-79.485946, 43.879945], [-79.481903, 43.880988], [-79.481466, 43.880467], [-79.48102, 43.879229], [-79.479559, 43.877269], [-79.475616, 43.876017], [-79.472591, 43.875122], [-79.471082, 43.872537], [-79.468365, 43.863982], [-79.46635, 43.861192], [-79.465885, 43.857078], [-79.465192, 43.854076], [-79.469861, 43.853103], [-79.469605, 43.849295], [-79.47039, 43.845481], [-79.46978, 43.84389], [-79.469368, 43.84257], [-79.469577, 43.840649], [-79.468849, 43.837858], [-79.468315, 43.835945], [-79.471802, 43.836479], [-79.475037, 43.83669], [-79.475086, 43.83554], [-79.474704, 43.833764], [-79.474179, 43.830841], [-79.47387, 43.828122], [-79.472772, 43.825685], [-79.471335, 43.825641], [-79.468038, 43.826334], [-79.464866, 43.827005], [-79.453091, 43.822544], [-79.452505, 43.820475], [-79.45187, 43.817555], [-79.451233, 43.814913], [-79.450243, 43.811349], [-79.453891, 43.809631]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_d9df826d16edd9ee59831d43fd6a15fe.bindTooltip(
                `<div>
                     470 WESTMOUNT SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_d9df826d16edd9ee59831d43fd6a15fe.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_80ad79dd6cee9a69d62bd327e84788ea_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_80ad79dd6cee9a69d62bd327e84788ea_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_80ad79dd6cee9a69d62bd327e84788ea = L.geoJson(null, {
                onEachFeature: geo_json_80ad79dd6cee9a69d62bd327e84788ea_onEachFeature,
            
                style: geo_json_80ad79dd6cee9a69d62bd327e84788ea_styler,
            ...{
}
        });

        function geo_json_80ad79dd6cee9a69d62bd327e84788ea_add (data) {
            geo_json_80ad79dd6cee9a69d62bd327e84788ea
                .addData(data);
        }
            geo_json_80ad79dd6cee9a69d62bd327e84788ea_add({"features": [{"geometry": {"coordinates": [[-79.454388, 43.809634], [-79.45019, 43.81265], [-79.450745, 43.814571], [-79.451357, 43.81695], [-79.452742, 43.822771], [-79.465218, 43.827051], [-79.467594, 43.826541], [-79.470806, 43.825866], [-79.473164, 43.82612], [-79.473557, 43.827517], [-79.473946, 43.829446], [-79.474553, 43.833893], [-79.475081, 43.836331], [-79.471865, 43.836374], [-79.468658, 43.835673], [-79.468636, 43.837566], [-79.469417, 43.84118], [-79.469243, 43.842754], [-79.469879, 43.84467], [-79.470464, 43.84618], [-79.469225, 43.848925], [-79.46989, 43.85283], [-79.467467, 43.853492], [-79.465819, 43.857284], [-79.46595, 43.860607], [-79.468268, 43.864625], [-79.470943, 43.872704], [-79.471879, 43.874742], [-79.474439, 43.875903], [-79.478994, 43.87698], [-79.482479, 43.875567], [-79.484685, 43.877361], [-79.485946, 43.879945], [-79.481903, 43.880988]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_80ad79dd6cee9a69d62bd327e84788ea.bindTooltip(
                `<div>
                     470 WESTMOUNT SS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_80ad79dd6cee9a69d62bd327e84788ea.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_a29a564c27272230a6e979610d9a9764_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_a29a564c27272230a6e979610d9a9764_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_a29a564c27272230a6e979610d9a9764 = L.geoJson(null, {
                onEachFeature: geo_json_a29a564c27272230a6e979610d9a9764_onEachFeature,
            
                style: geo_json_a29a564c27272230a6e979610d9a9764_styler,
            ...{
}
        });

        function geo_json_a29a564c27272230a6e979610d9a9764_add (data) {
            geo_json_a29a564c27272230a6e979610d9a9764
                .addData(data);
        }
            geo_json_a29a564c27272230a6e979610d9a9764_add({"features": [{"geometry": {"coordinates": [[-79.42546, 43.839813], [-79.430269, 43.839232], [-79.436214, 43.837963], [-79.439183, 43.837347], [-79.441343, 43.836112], [-79.440651, 43.83448], [-79.439924, 43.83268], [-79.454793, 43.832875], [-79.455218, 43.834045], [-79.457728, 43.836948], [-79.463244, 43.836346], [-79.466166, 43.836018], [-79.471802, 43.836479], [-79.475037, 43.83669], [-79.477867, 43.836394], [-79.481169, 43.835943], [-79.482683, 43.835804], [-79.48499, 43.835346], [-79.488109, 43.835348], [-79.492102, 43.836061], [-79.491583, 43.83729], [-79.491953, 43.840146], [-79.500233, 43.839244], [-79.502092, 43.838655], [-79.507436, 43.836714], [-79.513541, 43.835411], [-79.517067, 43.834686], [-79.521677, 43.833661], [-79.526454, 43.832629], [-79.53213, 43.827908], [-79.53437, 43.827187]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_a29a564c27272230a6e979610d9a9764.bindTooltip(
                `<div>
                     471 STEPHEN LEWIS SS VIA TEN OAKS
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_a29a564c27272230a6e979610d9a9764.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_df0c51fb302e566c40cf06d6f7557f09_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_df0c51fb302e566c40cf06d6f7557f09_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_df0c51fb302e566c40cf06d6f7557f09 = L.geoJson(null, {
                onEachFeature: geo_json_df0c51fb302e566c40cf06d6f7557f09_onEachFeature,
            
                style: geo_json_df0c51fb302e566c40cf06d6f7557f09_styler,
            ...{
}
        });

        function geo_json_df0c51fb302e566c40cf06d6f7557f09_add (data) {
            geo_json_df0c51fb302e566c40cf06d6f7557f09
                .addData(data);
        }
            geo_json_df0c51fb302e566c40cf06d6f7557f09_add({"features": [{"geometry": {"coordinates": [[-79.482479, 43.875567], [-79.484685, 43.877361], [-79.485946, 43.879945], [-79.481903, 43.880988], [-79.481466, 43.880467], [-79.48102, 43.879229], [-79.479559, 43.877269], [-79.475616, 43.876017], [-79.472591, 43.875122], [-79.471082, 43.872537], [-79.468365, 43.863982], [-79.46635, 43.861192], [-79.465885, 43.857078], [-79.465192, 43.854076], [-79.469861, 43.853103], [-79.469605, 43.849295], [-79.47039, 43.845481], [-79.46978, 43.84389], [-79.469368, 43.84257], [-79.469577, 43.840649], [-79.468849, 43.837858], [-79.468315, 43.835945], [-79.471802, 43.836479], [-79.475037, 43.83669], [-79.475086, 43.83554]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_df0c51fb302e566c40cf06d6f7557f09.bindTooltip(
                `<div>
                     473 STEPHEN LEWIS SS VIA THOMAS COOK
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_df0c51fb302e566c40cf06d6f7557f09.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_4be964becc043b0e4351dc1e79ca0c8d_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_4be964becc043b0e4351dc1e79ca0c8d_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_4be964becc043b0e4351dc1e79ca0c8d = L.geoJson(null, {
                onEachFeature: geo_json_4be964becc043b0e4351dc1e79ca0c8d_onEachFeature,
            
                style: geo_json_4be964becc043b0e4351dc1e79ca0c8d_styler,
            ...{
}
        });

        function geo_json_4be964becc043b0e4351dc1e79ca0c8d_add (data) {
            geo_json_4be964becc043b0e4351dc1e79ca0c8d
                .addData(data);
        }
            geo_json_4be964becc043b0e4351dc1e79ca0c8d_add({"features": [{"geometry": {"coordinates": [[-79.475081, 43.836331], [-79.471865, 43.836374], [-79.468658, 43.835673], [-79.468636, 43.837566], [-79.469417, 43.84118], [-79.469243, 43.842754], [-79.469879, 43.84467], [-79.470464, 43.84618], [-79.469225, 43.848925], [-79.46989, 43.85283], [-79.467467, 43.853492], [-79.465819, 43.857284], [-79.46595, 43.860607], [-79.468268, 43.864625], [-79.470943, 43.872704], [-79.471879, 43.874742], [-79.474439, 43.875903], [-79.478994, 43.87698], [-79.482479, 43.875567], [-79.484685, 43.877361], [-79.485946, 43.879945], [-79.481903, 43.880988]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_4be964becc043b0e4351dc1e79ca0c8d.bindTooltip(
                `<div>
                     473 STEPHEN LEWIS SS VIA THOMAS COOK
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_4be964becc043b0e4351dc1e79ca0c8d.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_570a507fdb1e367458efb5e0c13b56c3_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#F28AB2", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_570a507fdb1e367458efb5e0c13b56c3_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_570a507fdb1e367458efb5e0c13b56c3 = L.geoJson(null, {
                onEachFeature: geo_json_570a507fdb1e367458efb5e0c13b56c3_onEachFeature,
            
                style: geo_json_570a507fdb1e367458efb5e0c13b56c3_styler,
            ...{
}
        });

        function geo_json_570a507fdb1e367458efb5e0c13b56c3_add (data) {
            geo_json_570a507fdb1e367458efb5e0c13b56c3
                .addData(data);
        }
            geo_json_570a507fdb1e367458efb5e0c13b56c3_add({"features": [{"geometry": {"coordinates": [[-79.305968, 43.843384], [-79.310594, 43.842347], [-79.306631, 43.845769], [-79.306261, 43.854747], [-79.305354, 43.855789], [-79.303456, 43.857799], [-79.302588, 43.859408], [-79.30933, 43.861588], [-79.314372, 43.862174], [-79.309783, 43.861805], [-79.303919, 43.866377], [-79.29375, 43.867186], [-79.289437, 43.868789], [-79.286102, 43.874173], [-79.286677, 43.876826], [-79.286113, 43.877726], [-79.286547, 43.875043], [-79.283893, 43.874089], [-79.279986, 43.874509], [-79.272473, 43.870105], [-79.267082, 43.871371], [-79.266436, 43.872225], [-79.264292, 43.872027], [-79.259993, 43.874871], [-79.261663, 43.877713], [-79.263449, 43.87979], [-79.26187, 43.877833], [-79.260814, 43.877614], [-79.260181, 43.874952], [-79.257238, 43.874455], [-79.250125, 43.876169], [-79.243483, 43.87771], [-79.238146, 43.878932], [-79.235156, 43.880494], [-79.231434, 43.88057]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_570a507fdb1e367458efb5e0c13b56c3.bindTooltip(
                `<div>
                     522 MARKHAM LOCAL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_570a507fdb1e367458efb5e0c13b56c3.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_166e606cd93332599530bfd63317eec5_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#F28AB2", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_166e606cd93332599530bfd63317eec5_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_166e606cd93332599530bfd63317eec5 = L.geoJson(null, {
                onEachFeature: geo_json_166e606cd93332599530bfd63317eec5_onEachFeature,
            
                style: geo_json_166e606cd93332599530bfd63317eec5_styler,
            ...{
}
        });

        function geo_json_166e606cd93332599530bfd63317eec5_add (data) {
            geo_json_166e606cd93332599530bfd63317eec5
                .addData(data);
        }
            geo_json_166e606cd93332599530bfd63317eec5_add({"features": [{"geometry": {"coordinates": [[-79.231434, 43.88057], [-79.235961, 43.883962], [-79.235234, 43.884241], [-79.23453, 43.883324], [-79.232996, 43.883218], [-79.232901, 43.884803], [-79.229955, 43.885504], [-79.229499, 43.886931], [-79.229819, 43.888092], [-79.232011, 43.889528], [-79.237123, 43.887206], [-79.236317, 43.884493], [-79.240721, 43.883096], [-79.243408, 43.882443], [-79.252256, 43.880359], [-79.261663, 43.877713], [-79.263449, 43.87979], [-79.26187, 43.877833], [-79.260814, 43.877614], [-79.260181, 43.874952], [-79.260009, 43.874218], [-79.260273, 43.873906], [-79.26482, 43.872073], [-79.266436, 43.872225], [-79.271936, 43.870427], [-79.27729, 43.869189], [-79.280834, 43.8743], [-79.283893, 43.874089], [-79.286102, 43.874173], [-79.286677, 43.876826], [-79.286113, 43.877726], [-79.286547, 43.875043], [-79.286105, 43.872935], [-79.289437, 43.868789], [-79.294298, 43.867184], [-79.30933, 43.861588], [-79.314372, 43.862174], [-79.309783, 43.861805], [-79.303634, 43.86215], [-79.302821, 43.859806], [-79.303326, 43.858309], [-79.305193, 43.856339], [-79.307565, 43.853652], [-79.305834, 43.846266], [-79.306351, 43.844646], [-79.305968, 43.843384]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_166e606cd93332599530bfd63317eec5.bindTooltip(
                `<div>
                     522 MARKHAM LOCAL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_166e606cd93332599530bfd63317eec5.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_fab9405d5f6dd99aeb7a8fb23edf806c_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#F28AB2", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_fab9405d5f6dd99aeb7a8fb23edf806c_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_fab9405d5f6dd99aeb7a8fb23edf806c = L.geoJson(null, {
                onEachFeature: geo_json_fab9405d5f6dd99aeb7a8fb23edf806c_onEachFeature,
            
                style: geo_json_fab9405d5f6dd99aeb7a8fb23edf806c_styler,
            ...{
}
        });

        function geo_json_fab9405d5f6dd99aeb7a8fb23edf806c_add (data) {
            geo_json_fab9405d5f6dd99aeb7a8fb23edf806c
                .addData(data);
        }
            geo_json_fab9405d5f6dd99aeb7a8fb23edf806c_add({"features": [{"geometry": {"coordinates": [[-79.306351, 43.844646], [-79.305968, 43.843384]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_fab9405d5f6dd99aeb7a8fb23edf806c.bindTooltip(
                `<div>
                     522 MARKHAM LOCAL
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_fab9405d5f6dd99aeb7a8fb23edf806c.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_53ac334923318078aba61cad8cf12d77_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#009CDB", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_53ac334923318078aba61cad8cf12d77_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_53ac334923318078aba61cad8cf12d77 = L.geoJson(null, {
                onEachFeature: geo_json_53ac334923318078aba61cad8cf12d77_onEachFeature,
            
                style: geo_json_53ac334923318078aba61cad8cf12d77_styler,
            ...{
}
        });

        function geo_json_53ac334923318078aba61cad8cf12d77_add (data) {
            geo_json_53ac334923318078aba61cad8cf12d77
                .addData(data);
        }
            geo_json_53ac334923318078aba61cad8cf12d77_add({"features": [{"geometry": {"coordinates": [[-79.415497, 43.782133], [-79.42011, 43.798695], [-79.422192, 43.807001], [-79.424299, 43.816215], [-79.425788, 43.822633], [-79.425631, 43.839979], [-79.431511, 43.847009], [-79.433174, 43.853739], [-79.434857, 43.860929], [-79.436922, 43.869916], [-79.439272, 43.88046], [-79.441653, 43.890312], [-79.442777, 43.895489], [-79.445923, 43.908521], [-79.449146, 43.921873], [-79.454715, 43.945095], [-79.456268, 43.951671], [-79.458595, 43.962687], [-79.463698, 43.984317], [-79.465357, 43.990762], [-79.467575, 43.999943], [-79.469693, 44.008802], [-79.47364, 44.026442], [-79.476055, 44.03693], [-79.478257, 44.046147], [-79.480251, 44.054427], [-79.48644, 44.052893]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_53ac334923318078aba61cad8cf12d77.bindTooltip(
                `<div>
                     601 VIVA BLUE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_53ac334923318078aba61cad8cf12d77.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_5ee08e4621c50df6c9c9d012e52b967a_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#009CDB", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_5ee08e4621c50df6c9c9d012e52b967a_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_5ee08e4621c50df6c9c9d012e52b967a = L.geoJson(null, {
                onEachFeature: geo_json_5ee08e4621c50df6c9c9d012e52b967a_onEachFeature,
            
                style: geo_json_5ee08e4621c50df6c9c9d012e52b967a_styler,
            ...{
}
        });

        function geo_json_5ee08e4621c50df6c9c9d012e52b967a_add (data) {
            geo_json_5ee08e4621c50df6c9c9d012e52b967a
                .addData(data);
        }
            geo_json_5ee08e4621c50df6c9c9d012e52b967a_add({"features": [{"geometry": {"coordinates": [[-79.48644, 44.052893], [-79.480265, 44.054173], [-79.478038, 44.04484], [-79.47596, 44.035616], [-79.474094, 44.026787], [-79.469833, 44.00852], [-79.46778, 44.000178], [-79.465388, 43.99008], [-79.463744, 43.983182], [-79.459051, 43.963169], [-79.456443, 43.951598], [-79.45489, 43.944757], [-79.449919, 43.923781], [-79.445742, 43.907265], [-79.442618, 43.894221], [-79.44141, 43.888943], [-79.439322, 43.8795], [-79.436957, 43.869694], [-79.434594, 43.85951], [-79.432872, 43.852332], [-79.43136, 43.845794], [-79.425411, 43.840009], [-79.426035, 43.822276], [-79.424704, 43.816482], [-79.422566, 43.807246], [-79.420274, 43.798244], [-79.415497, 43.782133]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_5ee08e4621c50df6c9c9d012e52b967a.bindTooltip(
                `<div>
                     601 VIVA BLUE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_5ee08e4621c50df6c9c9d012e52b967a.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_487696a9230e0d844b00352bbe00ae41_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#009CDB", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_487696a9230e0d844b00352bbe00ae41_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_487696a9230e0d844b00352bbe00ae41 = L.geoJson(null, {
                onEachFeature: geo_json_487696a9230e0d844b00352bbe00ae41_onEachFeature,
            
                style: geo_json_487696a9230e0d844b00352bbe00ae41_styler,
            ...{
}
        });

        function geo_json_487696a9230e0d844b00352bbe00ae41_add (data) {
            geo_json_487696a9230e0d844b00352bbe00ae41
                .addData(data);
        }
            geo_json_487696a9230e0d844b00352bbe00ae41_add({"features": [{"geometry": {"coordinates": [[-79.425631, 43.839979], [-79.431511, 43.847009], [-79.433174, 43.853739], [-79.434857, 43.860929], [-79.436922, 43.869916], [-79.439272, 43.88046], [-79.441653, 43.890312], [-79.442777, 43.895489], [-79.445923, 43.908521], [-79.449146, 43.921873], [-79.454715, 43.945095], [-79.456268, 43.951671], [-79.458595, 43.962687], [-79.463698, 43.984317], [-79.465357, 43.990762], [-79.467575, 43.999943], [-79.469693, 44.008802], [-79.47364, 44.026442], [-79.476055, 44.03693], [-79.478257, 44.046147], [-79.480251, 44.054427], [-79.48644, 44.052893]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_487696a9230e0d844b00352bbe00ae41.bindTooltip(
                `<div>
                     601 VIVA BLUE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_487696a9230e0d844b00352bbe00ae41.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_d8d43e895ff1dccf425d82f536269dae_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#9461A8", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_d8d43e895ff1dccf425d82f536269dae_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_d8d43e895ff1dccf425d82f536269dae = L.geoJson(null, {
                onEachFeature: geo_json_d8d43e895ff1dccf425d82f536269dae_onEachFeature,
            
                style: geo_json_d8d43e895ff1dccf425d82f536269dae_styler,
            ...{
}
        });

        function geo_json_d8d43e895ff1dccf425d82f536269dae_add (data) {
            geo_json_d8d43e895ff1dccf425d82f536269dae
                .addData(data);
        }
            geo_json_d8d43e895ff1dccf425d82f536269dae_add({"features": [{"geometry": {"coordinates": [[-79.425598, 43.840199], [-79.405542, 43.840071], [-79.397566, 43.840774], [-79.391193, 43.842282], [-79.386044, 43.843494], [-79.381701, 43.844456], [-79.377206, 43.845498], [-79.363611, 43.848661], [-79.35856, 43.849755], [-79.35123, 43.851287], [-79.339783, 43.853934], [-79.332889, 43.855795], [-79.323604, 43.857991], [-79.315239, 43.859959], [-79.30894, 43.861433], [-79.302829, 43.862761], [-79.292103, 43.865302], [-79.283868, 43.867217], [-79.267082, 43.871371], [-79.259326, 43.873945], [-79.243483, 43.87771], [-79.232901, 43.884803], [-79.231759, 43.88052]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_d8d43e895ff1dccf425d82f536269dae.bindTooltip(
                `<div>
                     603 VIVA PURPLE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_d8d43e895ff1dccf425d82f536269dae.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_ddade5dae94cc18eb5b4fc5e46710d4a_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#9461A8", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_ddade5dae94cc18eb5b4fc5e46710d4a_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_ddade5dae94cc18eb5b4fc5e46710d4a = L.geoJson(null, {
                onEachFeature: geo_json_ddade5dae94cc18eb5b4fc5e46710d4a_onEachFeature,
            
                style: geo_json_ddade5dae94cc18eb5b4fc5e46710d4a_styler,
            ...{
}
        });

        function geo_json_ddade5dae94cc18eb5b4fc5e46710d4a_add (data) {
            geo_json_ddade5dae94cc18eb5b4fc5e46710d4a
                .addData(data);
        }
            geo_json_ddade5dae94cc18eb5b4fc5e46710d4a_add({"features": [{"geometry": {"coordinates": [[-79.378708, 43.845323], [-79.383281, 43.844221], [-79.387352, 43.843223], [-79.392761, 43.84207], [-79.399105, 43.840549], [-79.405394, 43.84019], [-79.425598, 43.840199]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_ddade5dae94cc18eb5b4fc5e46710d4a.bindTooltip(
                `<div>
                     603 VIVA PURPLE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_ddade5dae94cc18eb5b4fc5e46710d4a.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_1edffbed0ccee5ea0654fbe948f05714_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#9461A8", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_1edffbed0ccee5ea0654fbe948f05714_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_1edffbed0ccee5ea0654fbe948f05714 = L.geoJson(null, {
                onEachFeature: geo_json_1edffbed0ccee5ea0654fbe948f05714_onEachFeature,
            
                style: geo_json_1edffbed0ccee5ea0654fbe948f05714_styler,
            ...{
}
        });

        function geo_json_1edffbed0ccee5ea0654fbe948f05714_add (data) {
            geo_json_1edffbed0ccee5ea0654fbe948f05714
                .addData(data);
        }
            geo_json_1edffbed0ccee5ea0654fbe948f05714_add({"features": [{"geometry": {"coordinates": [[-79.231759, 43.88052], [-79.243027, 43.877991], [-79.260273, 43.873906], [-79.267589, 43.871474], [-79.285212, 43.86708], [-79.292544, 43.865408], [-79.304799, 43.862602], [-79.30933, 43.861588], [-79.314641, 43.860383], [-79.325598, 43.857823], [-79.334928, 43.855718], [-79.340128, 43.853922], [-79.352725, 43.851056], [-79.358978, 43.849739], [-79.363986, 43.848623], [-79.378708, 43.845323], [-79.383281, 43.844221], [-79.387352, 43.843223], [-79.392761, 43.84207], [-79.399105, 43.840549], [-79.405394, 43.84019], [-79.425598, 43.840199]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_1edffbed0ccee5ea0654fbe948f05714.bindTooltip(
                `<div>
                     603 VIVA PURPLE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_1edffbed0ccee5ea0654fbe948f05714.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_9695386963e73f03d3ca80f5cc7ba8dc_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#FBAF33", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_9695386963e73f03d3ca80f5cc7ba8dc_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_9695386963e73f03d3ca80f5cc7ba8dc = L.geoJson(null, {
                onEachFeature: geo_json_9695386963e73f03d3ca80f5cc7ba8dc_onEachFeature,
            
                style: geo_json_9695386963e73f03d3ca80f5cc7ba8dc_styler,
            ...{
}
        });

        function geo_json_9695386963e73f03d3ca80f5cc7ba8dc_add (data) {
            geo_json_9695386963e73f03d3ca80f5cc7ba8dc
                .addData(data);
        }
            geo_json_9695386963e73f03d3ca80f5cc7ba8dc_add({"features": [{"geometry": {"coordinates": [[-79.608653, 43.775925], [-79.597505, 43.778488], [-79.589548, 43.78047], [-79.578866, 43.78284], [-79.572199, 43.7842], [-79.555273, 43.787695], [-79.546424, 43.789586], [-79.532686, 43.792409], [-79.527503, 43.793416], [-79.517005, 43.795846], [-79.498735, 43.800464], [-79.473646, 43.805848], [-79.460025, 43.808758], [-79.454153, 43.810051], [-79.451702, 43.81788], [-79.453751, 43.832032], [-79.425775, 43.840195]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_9695386963e73f03d3ca80f5cc7ba8dc.bindTooltip(
                `<div>
                     605 VIVA ORANGE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_9695386963e73f03d3ca80f5cc7ba8dc.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_907486b0424065f341588feeefe395f6_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#FBAF33", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_907486b0424065f341588feeefe395f6_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_907486b0424065f341588feeefe395f6 = L.geoJson(null, {
                onEachFeature: geo_json_907486b0424065f341588feeefe395f6_onEachFeature,
            
                style: geo_json_907486b0424065f341588feeefe395f6_styler,
            ...{
}
        });

        function geo_json_907486b0424065f341588feeefe395f6_add (data) {
            geo_json_907486b0424065f341588feeefe395f6
                .addData(data);
        }
            geo_json_907486b0424065f341588feeefe395f6_add({"features": [{"geometry": {"coordinates": [[-79.425775, 43.840195], [-79.454167, 43.832096], [-79.451454, 43.816601], [-79.454532, 43.810014], [-79.461616, 43.808484], [-79.475549, 43.805524], [-79.500378, 43.800152], [-79.518738, 43.795526], [-79.52785, 43.793432], [-79.534405, 43.792094], [-79.548425, 43.78917], [-79.556974, 43.78751], [-79.573933, 43.783988], [-79.580427, 43.782625], [-79.590232, 43.780547], [-79.597043, 43.778903], [-79.609193, 43.775647]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_907486b0424065f341588feeefe395f6.bindTooltip(
                `<div>
                     605 VIVA ORANGE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_907486b0424065f341588feeefe395f6.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_3e11b055c2262d98105981ce95ec31d6_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#FFDD00", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_3e11b055c2262d98105981ce95ec31d6_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_3e11b055c2262d98105981ce95ec31d6 = L.geoJson(null, {
                onEachFeature: geo_json_3e11b055c2262d98105981ce95ec31d6_onEachFeature,
            
                style: geo_json_3e11b055c2262d98105981ce95ec31d6_styler,
            ...{
}
        });

        function geo_json_3e11b055c2262d98105981ce95ec31d6_add (data) {
            geo_json_3e11b055c2262d98105981ce95ec31d6
                .addData(data);
        }
            geo_json_3e11b055c2262d98105981ce95ec31d6_add({"features": [{"geometry": {"coordinates": [[-79.486222, 44.052742], [-79.471363, 44.056854], [-79.460406, 44.059292], [-79.450653, 44.061471], [-79.445031, 44.062665], [-79.431204, 44.065884], [-79.421104, 44.067627]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_3e11b055c2262d98105981ce95ec31d6.bindTooltip(
                `<div>
                     607 VIVA YELLOW
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_3e11b055c2262d98105981ce95ec31d6.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_af6879c8ce65359e62981c731e37ce00_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#FFDD00", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_af6879c8ce65359e62981c731e37ce00_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_af6879c8ce65359e62981c731e37ce00 = L.geoJson(null, {
                onEachFeature: geo_json_af6879c8ce65359e62981c731e37ce00_onEachFeature,
            
                style: geo_json_af6879c8ce65359e62981c731e37ce00_styler,
            ...{
}
        });

        function geo_json_af6879c8ce65359e62981c731e37ce00_add (data) {
            geo_json_af6879c8ce65359e62981c731e37ce00
                .addData(data);
        }
            geo_json_af6879c8ce65359e62981c731e37ce00_add({"features": [{"geometry": {"coordinates": [[-79.421104, 44.067627], [-79.432667, 44.065766], [-79.445579, 44.062777], [-79.452137, 44.061228], [-79.462001, 44.059011], [-79.472961, 44.056539], [-79.486222, 44.052742]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_af6879c8ce65359e62981c731e37ce00.bindTooltip(
                `<div>
                     607 VIVA YELLOW
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_af6879c8ce65359e62981c731e37ce00.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_5c0664b61ceb515e291a2632232f2c39_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#72BF44", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_5c0664b61ceb515e291a2632232f2c39_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_5c0664b61ceb515e291a2632232f2c39 = L.geoJson(null, {
                onEachFeature: geo_json_5c0664b61ceb515e291a2632232f2c39_onEachFeature,
            
                style: geo_json_5c0664b61ceb515e291a2632232f2c39_styler,
            ...{
}
        });

        function geo_json_5c0664b61ceb515e291a2632232f2c39_add (data) {
            geo_json_5c0664b61ceb515e291a2632232f2c39
                .addData(data);
        }
            geo_json_5c0664b61ceb515e291a2632232f2c39_add({"features": [{"geometry": {"coordinates": [[-79.436076, 43.857063], [-79.439394, 43.857245], [-79.440563, 43.858848], [-79.444738, 43.858199], [-79.445533, 43.860459], [-79.446245, 43.86243], [-79.446993, 43.864496], [-79.445548, 43.86715], [-79.448628, 43.868421], [-79.449247, 43.869988], [-79.45066, 43.873738], [-79.45123, 43.875799], [-79.448258, 43.876608], [-79.444782, 43.877321], [-79.442031, 43.877601], [-79.439378, 43.877887], [-79.438719, 43.880154], [-79.435105, 43.88097], [-79.429606, 43.88221], [-79.428701, 43.882548], [-79.425803, 43.883392], [-79.422847, 43.884053], [-79.417967, 43.885105], [-79.415586, 43.885612], [-79.413663, 43.886265], [-79.410907, 43.886877], [-79.407915, 43.887528], [-79.404139, 43.887648], [-79.401495, 43.888229], [-79.40047, 43.889299], [-79.400277, 43.892766], [-79.400055, 43.894163], [-79.400773, 43.897048], [-79.396114, 43.90054], [-79.398484, 43.902467]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_5c0664b61ceb515e291a2632232f2c39.bindTooltip(
                `<div>
                     8301 TRENCH
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_5c0664b61ceb515e291a2632232f2c39.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_ba5e6894620b8d22599dd5c099d5ca37_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#72BF44", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_ba5e6894620b8d22599dd5c099d5ca37_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_ba5e6894620b8d22599dd5c099d5ca37 = L.geoJson(null, {
                onEachFeature: geo_json_ba5e6894620b8d22599dd5c099d5ca37_onEachFeature,
            
                style: geo_json_ba5e6894620b8d22599dd5c099d5ca37_styler,
            ...{
}
        });

        function geo_json_ba5e6894620b8d22599dd5c099d5ca37_add (data) {
            geo_json_ba5e6894620b8d22599dd5c099d5ca37
                .addData(data);
        }
            geo_json_ba5e6894620b8d22599dd5c099d5ca37_add({"features": [{"geometry": {"coordinates": [[-79.398484, 43.902467], [-79.396565, 43.900932], [-79.396041, 43.898855], [-79.39687, 43.898337], [-79.400725, 43.896524], [-79.400286, 43.894752], [-79.40039, 43.89306], [-79.400388, 43.889652], [-79.403824, 43.887843], [-79.407531, 43.887709], [-79.4104, 43.887094], [-79.413281, 43.886472], [-79.41745, 43.885327], [-79.418293, 43.885157], [-79.422634, 43.884188], [-79.425659, 43.883561], [-79.430093, 43.882166], [-79.434311, 43.881256], [-79.439322, 43.8795], [-79.43898, 43.878121], [-79.441748, 43.877472], [-79.444441, 43.877457], [-79.448088, 43.876712], [-79.451059, 43.87608], [-79.450897, 43.874279], [-79.449496, 43.869987], [-79.44905, 43.86894], [-79.448577, 43.867894], [-79.445925, 43.867271], [-79.447055, 43.86483], [-79.446477, 43.862705], [-79.445821, 43.860887], [-79.445164, 43.858318], [-79.440848, 43.858897], [-79.439657, 43.857251], [-79.43506, 43.85822], [-79.436076, 43.857063]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_ba5e6894620b8d22599dd5c099d5ca37.bindTooltip(
                `<div>
                     8301 TRENCH
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_ba5e6894620b8d22599dd5c099d5ca37.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_81900d68ece6faf0ad522620e84e402a_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#F58220", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_81900d68ece6faf0ad522620e84e402a_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_81900d68ece6faf0ad522620e84e402a = L.geoJson(null, {
                onEachFeature: geo_json_81900d68ece6faf0ad522620e84e402a_onEachFeature,
            
                style: geo_json_81900d68ece6faf0ad522620e84e402a_styler,
            ...{
}
        });

        function geo_json_81900d68ece6faf0ad522620e84e402a_add (data) {
            geo_json_81900d68ece6faf0ad522620e84e402a
                .addData(data);
        }
            geo_json_81900d68ece6faf0ad522620e84e402a_add({"features": [{"geometry": {"coordinates": [[-79.346338, 43.775808], [-79.34784, 43.777548], [-79.348707, 43.779593], [-79.348945, 43.78272], [-79.350591, 43.7853], [-79.352814, 43.787264], [-79.353993, 43.790176], [-79.354514, 43.792438], [-79.355003, 43.794346], [-79.355097, 43.796288], [-79.354723, 43.797532], [-79.354036, 43.799454], [-79.353236, 43.802438], [-79.354962, 43.805409], [-79.356644, 43.806968], [-79.358763, 43.808857], [-79.360853, 43.81163], [-79.361859, 43.813989], [-79.366706, 43.8192], [-79.369799, 43.822068], [-79.370925, 43.826409], [-79.371997, 43.829491], [-79.377225, 43.831661], [-79.379357, 43.833513], [-79.378717, 43.839717], [-79.376918, 43.840285], [-79.375159, 43.841961], [-79.376818, 43.843686], [-79.378186, 43.846134], [-79.377728, 43.848472], [-79.37715, 43.849772], [-79.377688, 43.852442], [-79.378289, 43.854637], [-79.378927, 43.856457], [-79.380736, 43.857955], [-79.383506, 43.858202], [-79.384307, 43.860045], [-79.381425, 43.862441], [-79.382504, 43.865499], [-79.385611, 43.867234], [-79.386453, 43.869696], [-79.387789, 43.865758], [-79.387151, 43.862688], [-79.38573, 43.857149], [-79.387494, 43.856532], [-79.392512, 43.855393], [-79.392786, 43.851542], [-79.390391, 43.84981], [-79.388852, 43.849049], [-79.387699, 43.847532], [-79.387067, 43.845184], [-79.382711, 43.84415], [-79.37832, 43.845217], [-79.376898, 43.843611], [-79.375301, 43.841872], [-79.376974, 43.840397], [-79.378873, 43.839784]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_81900d68ece6faf0ad522620e84e402a.bindTooltip(
                `<div>
                     9002 LESLIE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_81900d68ece6faf0ad522620e84e402a.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_835c91901486d463616c1c8b745e7c34_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#F58220", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_835c91901486d463616c1c8b745e7c34_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_835c91901486d463616c1c8b745e7c34 = L.geoJson(null, {
                onEachFeature: geo_json_835c91901486d463616c1c8b745e7c34_onEachFeature,
            
                style: geo_json_835c91901486d463616c1c8b745e7c34_styler,
            ...{
}
        });

        function geo_json_835c91901486d463616c1c8b745e7c34_add (data) {
            geo_json_835c91901486d463616c1c8b745e7c34
                .addData(data);
        }
            geo_json_835c91901486d463616c1c8b745e7c34_add({"features": [{"geometry": {"coordinates": [[-79.346338, 43.775808], [-79.34784, 43.777548], [-79.348707, 43.779593], [-79.348945, 43.78272], [-79.350591, 43.7853], [-79.352814, 43.787264], [-79.353993, 43.790176], [-79.354514, 43.792438], [-79.355003, 43.794346], [-79.355097, 43.796288], [-79.354723, 43.797532], [-79.354036, 43.799454], [-79.353236, 43.802438], [-79.354962, 43.805409], [-79.356644, 43.806968], [-79.358763, 43.808857], [-79.360853, 43.81163], [-79.361859, 43.813989], [-79.366706, 43.8192], [-79.369799, 43.822068], [-79.370925, 43.826409], [-79.371997, 43.829491], [-79.377225, 43.831661], [-79.379357, 43.833513], [-79.378717, 43.839717], [-79.376918, 43.840285], [-79.375159, 43.841961], [-79.376818, 43.843686], [-79.378186, 43.846134]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_835c91901486d463616c1c8b745e7c34.bindTooltip(
                `<div>
                     9002 LESLIE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_835c91901486d463616c1c8b745e7c34.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_1ad4d000b15015f836ecdbe521bc22fc_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#F58220", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_1ad4d000b15015f836ecdbe521bc22fc_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_1ad4d000b15015f836ecdbe521bc22fc = L.geoJson(null, {
                onEachFeature: geo_json_1ad4d000b15015f836ecdbe521bc22fc_onEachFeature,
            
                style: geo_json_1ad4d000b15015f836ecdbe521bc22fc_styler,
            ...{
}
        });

        function geo_json_1ad4d000b15015f836ecdbe521bc22fc_add (data) {
            geo_json_1ad4d000b15015f836ecdbe521bc22fc
                .addData(data);
        }
            geo_json_1ad4d000b15015f836ecdbe521bc22fc_add({"features": [{"geometry": {"coordinates": [[-79.378873, 43.839784], [-79.379788, 43.833875], [-79.375664, 43.831165], [-79.372032, 43.829082], [-79.371314, 43.826734], [-79.369937, 43.82163], [-79.367274, 43.819227], [-79.362201, 43.814192], [-79.361138, 43.811731], [-79.35924, 43.809063], [-79.357016, 43.807101], [-79.354906, 43.805007], [-79.353481, 43.802539], [-79.354216, 43.799793], [-79.354822, 43.798001], [-79.355294, 43.796564], [-79.354963, 43.792903], [-79.354292, 43.790394], [-79.353216, 43.787472], [-79.353032, 43.78402], [-79.35234, 43.782346], [-79.345935, 43.779576], [-79.34506, 43.775683]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_1ad4d000b15015f836ecdbe521bc22fc.bindTooltip(
                `<div>
                     9002 LESLIE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_1ad4d000b15015f836ecdbe521bc22fc.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_de30c6ed93e946df6ecad8595e8629b8_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#F58220", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_de30c6ed93e946df6ecad8595e8629b8_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_de30c6ed93e946df6ecad8595e8629b8 = L.geoJson(null, {
                onEachFeature: geo_json_de30c6ed93e946df6ecad8595e8629b8_onEachFeature,
            
                style: geo_json_de30c6ed93e946df6ecad8595e8629b8_styler,
            ...{
}
        });

        function geo_json_de30c6ed93e946df6ecad8595e8629b8_add (data) {
            geo_json_de30c6ed93e946df6ecad8595e8629b8
                .addData(data);
        }
            geo_json_de30c6ed93e946df6ecad8595e8629b8_add({"features": [{"geometry": {"coordinates": [[-79.387067, 43.845184], [-79.382711, 43.84415], [-79.37832, 43.845217], [-79.376898, 43.843611], [-79.375301, 43.841872], [-79.376974, 43.840397], [-79.378873, 43.839784], [-79.379788, 43.833875], [-79.375664, 43.831165], [-79.372032, 43.829082], [-79.371314, 43.826734], [-79.369937, 43.82163], [-79.367274, 43.819227], [-79.362201, 43.814192], [-79.361138, 43.811731], [-79.35924, 43.809063], [-79.357016, 43.807101], [-79.354906, 43.805007], [-79.353481, 43.802539], [-79.354216, 43.799793], [-79.354822, 43.798001], [-79.355294, 43.796564], [-79.354963, 43.792903], [-79.354292, 43.790394], [-79.353216, 43.787472], [-79.353032, 43.78402], [-79.35234, 43.782346], [-79.345935, 43.779576], [-79.34506, 43.775683]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_de30c6ed93e946df6ecad8595e8629b8.bindTooltip(
                `<div>
                     9002 LESLIE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_de30c6ed93e946df6ecad8595e8629b8.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_c5e23dbd23828b87facd7a1caa73f4f7_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#F58220", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_c5e23dbd23828b87facd7a1caa73f4f7_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_c5e23dbd23828b87facd7a1caa73f4f7 = L.geoJson(null, {
                onEachFeature: geo_json_c5e23dbd23828b87facd7a1caa73f4f7_onEachFeature,
            
                style: geo_json_c5e23dbd23828b87facd7a1caa73f4f7_styler,
            ...{
}
        });

        function geo_json_c5e23dbd23828b87facd7a1caa73f4f7_add (data) {
            geo_json_c5e23dbd23828b87facd7a1caa73f4f7
                .addData(data);
        }
            geo_json_c5e23dbd23828b87facd7a1caa73f4f7_add({"features": [{"geometry": {"coordinates": [[-79.378186, 43.846134], [-79.377728, 43.848472], [-79.37715, 43.849772], [-79.377688, 43.852442], [-79.378289, 43.854637], [-79.378927, 43.856457], [-79.380736, 43.857955], [-79.383506, 43.858202], [-79.384307, 43.860045], [-79.381425, 43.862441], [-79.382504, 43.865499], [-79.385611, 43.867234], [-79.386453, 43.869696], [-79.387789, 43.865758], [-79.387151, 43.862688], [-79.38573, 43.857149], [-79.387494, 43.856532], [-79.392512, 43.855393], [-79.392786, 43.851542], [-79.390391, 43.84981], [-79.388852, 43.849049], [-79.387699, 43.847532], [-79.387067, 43.845184], [-79.382711, 43.84415], [-79.37832, 43.845217], [-79.376898, 43.843611], [-79.375301, 43.841872], [-79.376974, 43.840397], [-79.378873, 43.839784], [-79.379788, 43.833875], [-79.375664, 43.831165], [-79.372032, 43.829082], [-79.371314, 43.826734], [-79.369937, 43.82163], [-79.367274, 43.819227], [-79.362201, 43.814192], [-79.361138, 43.811731], [-79.35924, 43.809063], [-79.357016, 43.807101], [-79.354906, 43.805007], [-79.353481, 43.802539], [-79.354216, 43.799793], [-79.354822, 43.798001], [-79.355294, 43.796564], [-79.354963, 43.792903], [-79.354292, 43.790394], [-79.353216, 43.787472], [-79.353032, 43.78402], [-79.35234, 43.782346], [-79.345935, 43.779576], [-79.34506, 43.775683]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_c5e23dbd23828b87facd7a1caa73f4f7.bindTooltip(
                `<div>
                     9002 LESLIE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_c5e23dbd23828b87facd7a1caa73f4f7.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_2ffec069504f1344387ef7efa64f2792_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A37C53", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_2ffec069504f1344387ef7efa64f2792_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_2ffec069504f1344387ef7efa64f2792 = L.geoJson(null, {
                onEachFeature: geo_json_2ffec069504f1344387ef7efa64f2792_onEachFeature,
            
                style: geo_json_2ffec069504f1344387ef7efa64f2792_styler,
            ...{
}
        });

        function geo_json_2ffec069504f1344387ef7efa64f2792_add (data) {
            geo_json_2ffec069504f1344387ef7efa64f2792
                .addData(data);
        }
            geo_json_2ffec069504f1344387ef7efa64f2792_add({"features": [{"geometry": {"coordinates": [[-79.415048, 43.782136], [-79.416698, 43.78496], [-79.417335, 43.787532], [-79.417977, 43.790138], [-79.418316, 43.79149], [-79.418994, 43.794272], [-79.419892, 43.797916], [-79.41715, 43.798613], [-79.414578, 43.79915], [-79.411529, 43.799827], [-79.409432, 43.800293], [-79.405841, 43.801086], [-79.401813, 43.801966], [-79.397139, 43.804329], [-79.397983, 43.806131], [-79.398953, 43.810143], [-79.399528, 43.81249], [-79.400469, 43.816378], [-79.401031, 43.818961], [-79.401617, 43.821607], [-79.403256, 43.827992], [-79.403674, 43.829811], [-79.404444, 43.832527], [-79.404949, 43.834622], [-79.406529, 43.840517], [-79.407004, 43.842388], [-79.407656, 43.844919], [-79.40843, 43.847824], [-79.409373, 43.851765], [-79.409951, 43.854023], [-79.410517, 43.856027], [-79.410794, 43.857606], [-79.411642, 43.86081], [-79.41203, 43.862578], [-79.413098, 43.866798], [-79.413516, 43.86868], [-79.414324, 43.872027], [-79.41524, 43.875816], [-79.415764, 43.878074], [-79.416166, 43.87967], [-79.416943, 43.882699], [-79.417503, 43.885009], [-79.418288, 43.888158], [-79.418977, 43.890745], [-79.419582, 43.893312], [-79.420348, 43.896509], [-79.422094, 43.900157], [-79.426044, 43.899903], [-79.426399, 43.901717], [-79.42626, 43.903032], [-79.422683, 43.903991]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_2ffec069504f1344387ef7efa64f2792.bindTooltip(
                `<div>
                     9101 BAYVIEW
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_2ffec069504f1344387ef7efa64f2792.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_7d26c8ba128e914f6e90925503fc0425_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A37C53", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_7d26c8ba128e914f6e90925503fc0425_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_7d26c8ba128e914f6e90925503fc0425 = L.geoJson(null, {
                onEachFeature: geo_json_7d26c8ba128e914f6e90925503fc0425_onEachFeature,
            
                style: geo_json_7d26c8ba128e914f6e90925503fc0425_styler,
            ...{
}
        });

        function geo_json_7d26c8ba128e914f6e90925503fc0425_add (data) {
            geo_json_7d26c8ba128e914f6e90925503fc0425
                .addData(data);
        }
            geo_json_7d26c8ba128e914f6e90925503fc0425_add({"features": [{"geometry": {"coordinates": [[-79.422683, 43.903991], [-79.422446, 43.903785], [-79.421569, 43.900484], [-79.42106, 43.89854], [-79.420421, 43.896226], [-79.419986, 43.893855], [-79.419551, 43.892149], [-79.419037, 43.889982], [-79.4184, 43.887486], [-79.417865, 43.885392], [-79.417259, 43.882953], [-79.416569, 43.880167], [-79.416026, 43.877896], [-79.415424, 43.875413], [-79.414715, 43.872415], [-79.413927, 43.869023], [-79.413427, 43.867023], [-79.412405, 43.862989], [-79.411969, 43.861189], [-79.411239, 43.858141], [-79.410691, 43.856002], [-79.410168, 43.853831], [-79.409795, 43.852127], [-79.408834, 43.848219], [-79.408127, 43.845365], [-79.407322, 43.84223], [-79.406651, 43.839751], [-79.405387, 43.834918], [-79.404746, 43.832438], [-79.404126, 43.830088], [-79.403553, 43.827828], [-79.402064, 43.821857], [-79.401553, 43.819937], [-79.401208, 43.81825], [-79.400684, 43.81622], [-79.399895, 43.81278], [-79.399214, 43.809846], [-79.39832, 43.806439], [-79.396684, 43.803491], [-79.3976, 43.803048], [-79.400758, 43.802356], [-79.406159, 43.801191], [-79.409216, 43.800515], [-79.411703, 43.799966], [-79.414376, 43.799391], [-79.417001, 43.798816], [-79.419718, 43.796088], [-79.419191, 43.793992], [-79.418625, 43.791289], [-79.418069, 43.789452], [-79.417496, 43.7872], [-79.415048, 43.782136]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_7d26c8ba128e914f6e90925503fc0425.bindTooltip(
                `<div>
                     9101 BAYVIEW
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_7d26c8ba128e914f6e90925503fc0425.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_8e373bddc8138e89720cd79e39702cf3_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A37C53", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_8e373bddc8138e89720cd79e39702cf3_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_8e373bddc8138e89720cd79e39702cf3 = L.geoJson(null, {
                onEachFeature: geo_json_8e373bddc8138e89720cd79e39702cf3_onEachFeature,
            
                style: geo_json_8e373bddc8138e89720cd79e39702cf3_styler,
            ...{
}
        });

        function geo_json_8e373bddc8138e89720cd79e39702cf3_add (data) {
            geo_json_8e373bddc8138e89720cd79e39702cf3
                .addData(data);
        }
            geo_json_8e373bddc8138e89720cd79e39702cf3_add({"features": [{"geometry": {"coordinates": [[-79.401031, 43.818961], [-79.401617, 43.821607], [-79.403256, 43.827992], [-79.403674, 43.829811], [-79.404444, 43.832527], [-79.404949, 43.834622], [-79.406529, 43.840517], [-79.407004, 43.842388], [-79.407656, 43.844919], [-79.40843, 43.847824], [-79.409373, 43.851765], [-79.409951, 43.854023], [-79.410517, 43.856027], [-79.410794, 43.857606], [-79.411642, 43.86081], [-79.41203, 43.862578], [-79.413098, 43.866798], [-79.413516, 43.86868], [-79.414324, 43.872027], [-79.41524, 43.875816], [-79.415764, 43.878074], [-79.416166, 43.87967], [-79.416943, 43.882699], [-79.417503, 43.885009], [-79.418288, 43.888158], [-79.418977, 43.890745], [-79.419582, 43.893312], [-79.420348, 43.896509], [-79.422094, 43.900157], [-79.426044, 43.899903], [-79.426399, 43.901717], [-79.42626, 43.903032], [-79.422683, 43.903991]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_8e373bddc8138e89720cd79e39702cf3.bindTooltip(
                `<div>
                     9101 BAYVIEW
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_8e373bddc8138e89720cd79e39702cf3.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_978c675946de67ef06d152b3fdcf65a6_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A37C53", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_978c675946de67ef06d152b3fdcf65a6_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_978c675946de67ef06d152b3fdcf65a6 = L.geoJson(null, {
                onEachFeature: geo_json_978c675946de67ef06d152b3fdcf65a6_onEachFeature,
            
                style: geo_json_978c675946de67ef06d152b3fdcf65a6_styler,
            ...{
}
        });

        function geo_json_978c675946de67ef06d152b3fdcf65a6_add (data) {
            geo_json_978c675946de67ef06d152b3fdcf65a6
                .addData(data);
        }
            geo_json_978c675946de67ef06d152b3fdcf65a6_add({"features": [{"geometry": {"coordinates": [[-79.42523, 43.839711], [-79.407656, 43.844919], [-79.40843, 43.847824], [-79.409373, 43.851765], [-79.409951, 43.854023], [-79.410517, 43.856027], [-79.410794, 43.857606], [-79.411642, 43.86081], [-79.41203, 43.862578], [-79.413098, 43.866798], [-79.413516, 43.86868], [-79.414324, 43.872027], [-79.41524, 43.875816], [-79.415764, 43.878074], [-79.416166, 43.87967], [-79.416943, 43.882699], [-79.417503, 43.885009], [-79.418288, 43.888158], [-79.418977, 43.890745], [-79.419582, 43.893312], [-79.420348, 43.896509], [-79.421185, 43.899955], [-79.422572, 43.905557], [-79.423973, 43.910831], [-79.425534, 43.917325], [-79.426269, 43.921015], [-79.427312, 43.925232], [-79.428495, 43.930885], [-79.430848, 43.940212], [-79.434033, 43.93932], [-79.438132, 43.939162], [-79.441791, 43.938597], [-79.44726, 43.939313], [-79.453278, 43.939973], [-79.453832, 43.941634], [-79.454238, 43.943311], [-79.454715, 43.945095], [-79.455386, 43.948224], [-79.455859, 43.950171], [-79.456268, 43.951671], [-79.456841, 43.954832], [-79.455648, 43.954934], [-79.452865, 43.955097], [-79.448586, 43.955554], [-79.443343, 43.956549], [-79.442549, 43.95468], [-79.44296, 43.951159], [-79.441484, 43.95139], [-79.439451, 43.952004], [-79.436636, 43.952912], [-79.434831, 43.953313], [-79.432681, 43.953778], [-79.428141, 43.950389], [-79.42753, 43.946294], [-79.428498, 43.943388], [-79.429576, 43.940148]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_978c675946de67ef06d152b3fdcf65a6.bindTooltip(
                `<div>
                     9102 BAYVIEW
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_978c675946de67ef06d152b3fdcf65a6.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_39894c1bcf4d433ebd38f0a5a022c168_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A37C53", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_39894c1bcf4d433ebd38f0a5a022c168_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_39894c1bcf4d433ebd38f0a5a022c168 = L.geoJson(null, {
                onEachFeature: geo_json_39894c1bcf4d433ebd38f0a5a022c168_onEachFeature,
            
                style: geo_json_39894c1bcf4d433ebd38f0a5a022c168_styler,
            ...{
}
        });

        function geo_json_39894c1bcf4d433ebd38f0a5a022c168_add (data) {
            geo_json_39894c1bcf4d433ebd38f0a5a022c168
                .addData(data);
        }
            geo_json_39894c1bcf4d433ebd38f0a5a022c168_add({"features": [{"geometry": {"coordinates": [[-79.42523, 43.839711], [-79.407656, 43.844919], [-79.40843, 43.847824], [-79.409373, 43.851765], [-79.409951, 43.854023], [-79.410517, 43.856027], [-79.410794, 43.857606], [-79.411642, 43.86081], [-79.41203, 43.862578], [-79.413098, 43.866798], [-79.413516, 43.86868], [-79.414324, 43.872027], [-79.41524, 43.875816], [-79.415764, 43.878074], [-79.416166, 43.87967], [-79.416943, 43.882699], [-79.417503, 43.885009], [-79.418288, 43.888158], [-79.418977, 43.890745], [-79.419582, 43.893312], [-79.420348, 43.896509], [-79.421185, 43.899955], [-79.422572, 43.905557], [-79.423973, 43.910831], [-79.425534, 43.917325], [-79.426269, 43.921015], [-79.427312, 43.925232], [-79.428495, 43.930885], [-79.429443, 43.939749]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_39894c1bcf4d433ebd38f0a5a022c168.bindTooltip(
                `<div>
                     9102 BAYVIEW
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_39894c1bcf4d433ebd38f0a5a022c168.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_349c2996183b370f052937c9f69ab992_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A37C53", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_349c2996183b370f052937c9f69ab992_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_349c2996183b370f052937c9f69ab992 = L.geoJson(null, {
                onEachFeature: geo_json_349c2996183b370f052937c9f69ab992_onEachFeature,
            
                style: geo_json_349c2996183b370f052937c9f69ab992_styler,
            ...{
}
        });

        function geo_json_349c2996183b370f052937c9f69ab992_add (data) {
            geo_json_349c2996183b370f052937c9f69ab992
                .addData(data);
        }
            geo_json_349c2996183b370f052937c9f69ab992_add({"features": [{"geometry": {"coordinates": [[-79.429576, 43.940148], [-79.428897, 43.931261], [-79.42761, 43.925673], [-79.4259, 43.917862], [-79.424346, 43.911453], [-79.423027, 43.906169], [-79.422446, 43.903785], [-79.421569, 43.900484], [-79.42106, 43.89854], [-79.420421, 43.896226], [-79.419986, 43.893855], [-79.419551, 43.892149], [-79.419037, 43.889982], [-79.4184, 43.887486], [-79.417865, 43.885392], [-79.417259, 43.882953], [-79.416569, 43.880167], [-79.416026, 43.877896], [-79.415424, 43.875413], [-79.414715, 43.872415], [-79.413927, 43.869023], [-79.413427, 43.867023], [-79.412405, 43.862989], [-79.411969, 43.861189], [-79.411239, 43.858141], [-79.410691, 43.856002], [-79.410168, 43.853831], [-79.409795, 43.852127], [-79.408834, 43.848219], [-79.408127, 43.845365], [-79.42523, 43.839711]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_349c2996183b370f052937c9f69ab992.bindTooltip(
                `<div>
                     9102 BAYVIEW
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_349c2996183b370f052937c9f69ab992.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_19a8888f6e4299daa41f454820e74597_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A37C53", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_19a8888f6e4299daa41f454820e74597_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_19a8888f6e4299daa41f454820e74597 = L.geoJson(null, {
                onEachFeature: geo_json_19a8888f6e4299daa41f454820e74597_onEachFeature,
            
                style: geo_json_19a8888f6e4299daa41f454820e74597_styler,
            ...{
}
        });

        function geo_json_19a8888f6e4299daa41f454820e74597_add (data) {
            geo_json_19a8888f6e4299daa41f454820e74597
                .addData(data);
        }
            geo_json_19a8888f6e4299daa41f454820e74597_add({"features": [{"geometry": {"coordinates": [[-79.429443, 43.939749], [-79.427738, 43.949958], [-79.432413, 43.953954], [-79.434733, 43.953429], [-79.436894, 43.952947], [-79.438964, 43.952204], [-79.441043, 43.951616], [-79.442938, 43.951473], [-79.442618, 43.954356], [-79.44292, 43.956254], [-79.448692, 43.955676], [-79.451732, 43.955453], [-79.456443, 43.951598], [-79.456186, 43.950338], [-79.455809, 43.948727], [-79.45532, 43.946664], [-79.45489, 43.944757], [-79.454291, 43.942266], [-79.452893, 43.939905], [-79.446077, 43.938431], [-79.442052, 43.938477], [-79.43863, 43.939128], [-79.434459, 43.939031], [-79.42978, 43.939944], [-79.428897, 43.931261], [-79.42761, 43.925673], [-79.4259, 43.917862], [-79.424346, 43.911453], [-79.423027, 43.906169], [-79.422446, 43.903785], [-79.421569, 43.900484], [-79.42106, 43.89854], [-79.420421, 43.896226], [-79.419986, 43.893855], [-79.419551, 43.892149], [-79.419037, 43.889982], [-79.4184, 43.887486], [-79.417865, 43.885392], [-79.417259, 43.882953], [-79.416569, 43.880167], [-79.416026, 43.877896], [-79.415424, 43.875413], [-79.414715, 43.872415], [-79.413927, 43.869023], [-79.413427, 43.867023], [-79.412405, 43.862989], [-79.411969, 43.861189], [-79.411239, 43.858141], [-79.410691, 43.856002], [-79.410168, 43.853831], [-79.409795, 43.852127], [-79.408834, 43.848219], [-79.408127, 43.845365], [-79.42523, 43.839711]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_19a8888f6e4299daa41f454820e74597.bindTooltip(
                `<div>
                     9102 BAYVIEW
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_19a8888f6e4299daa41f454820e74597.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_ff6a4cb312f677d65375b0983527448d_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#007647", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_ff6a4cb312f677d65375b0983527448d_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_ff6a4cb312f677d65375b0983527448d = L.geoJson(null, {
                onEachFeature: geo_json_ff6a4cb312f677d65375b0983527448d_onEachFeature,
            
                style: geo_json_ff6a4cb312f677d65375b0983527448d_styler,
            ...{
}
        });

        function geo_json_ff6a4cb312f677d65375b0983527448d_add (data) {
            geo_json_ff6a4cb312f677d65375b0983527448d
                .addData(data);
        }
            geo_json_ff6a4cb312f677d65375b0983527448d_add({"features": [{"geometry": {"coordinates": [[-79.414795, 43.782426], [-79.416698, 43.78496], [-79.417335, 43.787532], [-79.417977, 43.790138], [-79.418316, 43.79149], [-79.418994, 43.794272], [-79.42011, 43.798695], [-79.420878, 43.801684], [-79.421756, 43.805238], [-79.422192, 43.807001], [-79.423127, 43.810912], [-79.42381, 43.814029], [-79.424299, 43.816215], [-79.425788, 43.822633], [-79.426318, 43.824924], [-79.426813, 43.827024], [-79.427303, 43.828884], [-79.427555, 43.830103], [-79.428022, 43.832324], [-79.429307, 43.838465], [-79.425301, 43.83968], [-79.429968, 43.841201], [-79.430649, 43.844229], [-79.431258, 43.846668], [-79.43183, 43.848956], [-79.432374, 43.851295], [-79.432974, 43.853602], [-79.43334, 43.855265], [-79.434036, 43.858256], [-79.434437, 43.860022], [-79.434891, 43.861968], [-79.435279, 43.863709], [-79.435931, 43.866482], [-79.436556, 43.869222], [-79.43693, 43.870716], [-79.437717, 43.874235], [-79.438224, 43.876169], [-79.438754, 43.878261], [-79.439272, 43.88046], [-79.439731, 43.882565], [-79.440261, 43.884941], [-79.440604, 43.886598], [-79.441423, 43.890207], [-79.44235, 43.894633], [-79.443299, 43.89848], [-79.444081, 43.901573], [-79.444742, 43.904543], [-79.445549, 43.907563], [-79.446548, 43.911482], [-79.447089, 43.913846], [-79.447782, 43.916541], [-79.449146, 43.921873], [-79.450276, 43.925991], [-79.451267, 43.92901], [-79.45338, 43.939615], [-79.453832, 43.941634], [-79.454238, 43.943311], [-79.454715, 43.945095], [-79.455386, 43.948224], [-79.455859, 43.950171], [-79.456268, 43.951671], [-79.456841, 43.954832], [-79.457668, 43.958441], [-79.458595, 43.962687], [-79.459201, 43.965164], [-79.460094, 43.96891], [-79.461004, 43.972623], [-79.462081, 43.977299], [-79.462813, 43.980635], [-79.463698, 43.984317], [-79.464179, 43.986377], [-79.46446, 43.987502], [-79.465357, 43.990762], [-79.466121, 43.994063], [-79.466738, 43.996631], [-79.467575, 43.999943], [-79.468538, 44.004002], [-79.469037, 44.00628], [-79.469693, 44.008802], [-79.47081, 44.01389], [-79.472084, 44.019356], [-79.47364, 44.026442], [-79.475045, 44.032599], [-79.475434, 44.034363], [-79.475949, 44.03673], [-79.476668, 44.039916], [-79.4792, 44.045301], [-79.482157, 44.044815], [-79.484305, 44.046441], [-79.484627, 44.048227], [-79.484517, 44.049968], [-79.484547, 44.051922], [-79.486433, 44.052662], [-79.485781, 44.053567], [-79.48104, 44.05851], [-79.481709, 44.060872], [-79.48247, 44.064102], [-79.483384, 44.067795], [-79.487458, 44.071061], [-79.485451, 44.072654]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_ff6a4cb312f677d65375b0983527448d.bindTooltip(
                `<div>
                     9899 YONGE (LATE NIGHT)
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_ff6a4cb312f677d65375b0983527448d.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_cb95da3c9a8c3b213703245281e9bf3a_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#007647", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_cb95da3c9a8c3b213703245281e9bf3a_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_cb95da3c9a8c3b213703245281e9bf3a = L.geoJson(null, {
                onEachFeature: geo_json_cb95da3c9a8c3b213703245281e9bf3a_onEachFeature,
            
                style: geo_json_cb95da3c9a8c3b213703245281e9bf3a_styler,
            ...{
}
        });

        function geo_json_cb95da3c9a8c3b213703245281e9bf3a_add (data) {
            geo_json_cb95da3c9a8c3b213703245281e9bf3a
                .addData(data);
        }
            geo_json_cb95da3c9a8c3b213703245281e9bf3a_add({"features": [{"geometry": {"coordinates": [[-79.414795, 43.782426], [-79.416698, 43.78496], [-79.417335, 43.787532], [-79.417977, 43.790138], [-79.418316, 43.79149], [-79.418994, 43.794272], [-79.42011, 43.798695], [-79.420878, 43.801684], [-79.421756, 43.805238], [-79.422192, 43.807001], [-79.423127, 43.810912], [-79.42381, 43.814029], [-79.424299, 43.816215], [-79.425788, 43.822633], [-79.426318, 43.824924], [-79.426813, 43.827024], [-79.427303, 43.828884], [-79.427555, 43.830103], [-79.428022, 43.832324], [-79.429307, 43.838465], [-79.425301, 43.83968], [-79.429968, 43.841201], [-79.430649, 43.844229], [-79.431258, 43.846668], [-79.43183, 43.848956], [-79.432374, 43.851295], [-79.432974, 43.853602], [-79.43334, 43.855265], [-79.434036, 43.858256], [-79.434437, 43.860022], [-79.434891, 43.861968], [-79.435279, 43.863709], [-79.435931, 43.866482], [-79.436556, 43.869222], [-79.43693, 43.870716], [-79.437717, 43.874235], [-79.438224, 43.876169], [-79.438754, 43.878261], [-79.439272, 43.88046], [-79.439731, 43.882565], [-79.440261, 43.884941], [-79.440604, 43.886598], [-79.441423, 43.890207], [-79.44235, 43.894633], [-79.443299, 43.89848], [-79.444081, 43.901573], [-79.444742, 43.904543], [-79.445549, 43.907563], [-79.446548, 43.911482], [-79.447089, 43.913846], [-79.447782, 43.916541], [-79.449146, 43.921873], [-79.450276, 43.925991], [-79.451267, 43.92901], [-79.45338, 43.939615], [-79.453832, 43.941634], [-79.454238, 43.943311], [-79.454715, 43.945095], [-79.455386, 43.948224], [-79.455859, 43.950171], [-79.456268, 43.951671], [-79.456841, 43.954832], [-79.457668, 43.958441], [-79.458595, 43.962687], [-79.459201, 43.965164], [-79.460094, 43.96891], [-79.461004, 43.972623], [-79.462081, 43.977299], [-79.462813, 43.980635], [-79.463698, 43.984317], [-79.464179, 43.986377], [-79.46446, 43.987502], [-79.465357, 43.990762], [-79.466121, 43.994063], [-79.466738, 43.996631], [-79.467575, 43.999943], [-79.468538, 44.004002], [-79.469037, 44.00628], [-79.469693, 44.008802], [-79.47081, 44.01389], [-79.472084, 44.019356], [-79.47364, 44.026442], [-79.475045, 44.032599], [-79.475434, 44.034363], [-79.475949, 44.03673], [-79.476668, 44.039916], [-79.4792, 44.045301], [-79.482157, 44.044815], [-79.484305, 44.046441], [-79.484627, 44.048227], [-79.484517, 44.049968], [-79.484547, 44.051922], [-79.486433, 44.052662]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_cb95da3c9a8c3b213703245281e9bf3a.bindTooltip(
                `<div>
                     9899 YONGE (LATE NIGHT)
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_cb95da3c9a8c3b213703245281e9bf3a.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_d379d186b5e1369fded43477a856128c_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#007647", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_d379d186b5e1369fded43477a856128c_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_d379d186b5e1369fded43477a856128c = L.geoJson(null, {
                onEachFeature: geo_json_d379d186b5e1369fded43477a856128c_onEachFeature,
            
                style: geo_json_d379d186b5e1369fded43477a856128c_styler,
            ...{
}
        });

        function geo_json_d379d186b5e1369fded43477a856128c_add (data) {
            geo_json_d379d186b5e1369fded43477a856128c
                .addData(data);
        }
            geo_json_d379d186b5e1369fded43477a856128c_add({"features": [{"geometry": {"coordinates": [[-79.485451, 44.072654], [-79.484559, 44.071102], [-79.483827, 44.068092], [-79.483455, 44.066601], [-79.482941, 44.064597], [-79.482177, 44.061349], [-79.480711, 44.055096], [-79.483716, 44.054279], [-79.486433, 44.052662], [-79.485781, 44.053567], [-79.483007, 44.054155], [-79.48074, 44.054598], [-79.480129, 44.053025], [-79.479677, 44.051177], [-79.479298, 44.049546], [-79.478882, 44.047833], [-79.478478, 44.045766], [-79.477146, 44.040394], [-79.476136, 44.035685], [-79.475459, 44.033086], [-79.474094, 44.026787], [-79.472208, 44.01845], [-79.471047, 44.013564], [-79.469833, 44.00852], [-79.469345, 44.006481], [-79.468625, 44.003562], [-79.46778, 44.000178], [-79.46697, 43.996791], [-79.466302, 43.994172], [-79.465388, 43.99008], [-79.464662, 43.986869], [-79.463744, 43.983182], [-79.46255, 43.977941], [-79.461297, 43.972606], [-79.460309, 43.968505], [-79.459051, 43.963169], [-79.458209, 43.959468], [-79.457341, 43.955254], [-79.456443, 43.951598], [-79.456186, 43.950338], [-79.455809, 43.948727], [-79.45532, 43.946664], [-79.45489, 43.944757], [-79.454291, 43.942266], [-79.453825, 43.940082], [-79.451745, 43.929207], [-79.450616, 43.926214], [-79.449919, 43.923781], [-79.448117, 43.916596], [-79.447534, 43.914257], [-79.446945, 43.911874], [-79.446084, 43.908107], [-79.445298, 43.90495], [-79.444488, 43.901299], [-79.443908, 43.898838], [-79.44295, 43.895054], [-79.441599, 43.889039], [-79.441063, 43.886954], [-79.440636, 43.885006], [-79.440034, 43.882786], [-79.439322, 43.8795], [-79.43898, 43.878121], [-79.438322, 43.875626], [-79.437899, 43.873782], [-79.437395, 43.871435], [-79.437086, 43.869505], [-79.436474, 43.86678], [-79.435828, 43.864177], [-79.435526, 43.862826], [-79.435013, 43.860639], [-79.434583, 43.858768], [-79.433883, 43.855794], [-79.433308, 43.853302], [-79.432818, 43.851521], [-79.432549, 43.850147], [-79.432098, 43.848431], [-79.431706, 43.846539], [-79.431204, 43.84459], [-79.430455, 43.841704], [-79.42523, 43.839711], [-79.429701, 43.83824], [-79.429351, 43.836591], [-79.428506, 43.832738], [-79.42804, 43.83072], [-79.427575, 43.828851], [-79.427091, 43.826823], [-79.42672, 43.825278], [-79.426035, 43.822276], [-79.424704, 43.816482], [-79.424259, 43.814736], [-79.423491, 43.811126], [-79.422566, 43.807246], [-79.422211, 43.805597], [-79.4213, 43.802036], [-79.420274, 43.798244], [-79.420037, 43.797434], [-79.419718, 43.796088], [-79.419191, 43.793992], [-79.418625, 43.791289], [-79.418069, 43.789452], [-79.417496, 43.7872], [-79.414795, 43.782426]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_d379d186b5e1369fded43477a856128c.bindTooltip(
                `<div>
                     9899 YONGE (LATE NIGHT)
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_d379d186b5e1369fded43477a856128c.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_c0cf61d619a63103cc05c4ec42965332_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00B547", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_c0cf61d619a63103cc05c4ec42965332_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_c0cf61d619a63103cc05c4ec42965332 = L.geoJson(null, {
                onEachFeature: geo_json_c0cf61d619a63103cc05c4ec42965332_onEachFeature,
            
                style: geo_json_c0cf61d619a63103cc05c4ec42965332_styler,
            ...{
}
        });

        function geo_json_c0cf61d619a63103cc05c4ec42965332_add (data) {
            geo_json_c0cf61d619a63103cc05c4ec42965332
                .addData(data);
        }
            geo_json_c0cf61d619a63103cc05c4ec42965332_add({"features": [{"geometry": {"coordinates": [[-79.512542, 43.77902], [-79.507342, 43.778448], [-79.503784, 43.779254], [-79.49483, 43.783164], [-79.495866, 43.786778], [-79.496384, 43.788729], [-79.498282, 43.796425], [-79.499094, 43.799931], [-79.49991, 43.802942], [-79.500702, 43.806213], [-79.501263, 43.808497], [-79.497891, 43.809523], [-79.49334, 43.810126], [-79.488801, 43.81105], [-79.483488, 43.812324], [-79.483036, 43.81399], [-79.483328, 43.816101], [-79.483649, 43.817638], [-79.484149, 43.819729], [-79.484674, 43.822119], [-79.49081, 43.82149], [-79.498673, 43.81979], [-79.498794, 43.821098], [-79.497474, 43.823846], [-79.497979, 43.827096], [-79.498796, 43.830148], [-79.499188, 43.832846], [-79.499857, 43.835415], [-79.500366, 43.836939], [-79.501915, 43.838016], [-79.49986, 43.83871]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_c0cf61d619a63103cc05c4ec42965332.bindTooltip(
                `<div>
                     10702 KEELE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_c0cf61d619a63103cc05c4ec42965332.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_dadc2a771256393506fb03862aa6c695_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#00B547", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_dadc2a771256393506fb03862aa6c695_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_dadc2a771256393506fb03862aa6c695 = L.geoJson(null, {
                onEachFeature: geo_json_dadc2a771256393506fb03862aa6c695_onEachFeature,
            
                style: geo_json_dadc2a771256393506fb03862aa6c695_styler,
            ...{
}
        });

        function geo_json_dadc2a771256393506fb03862aa6c695_add (data) {
            geo_json_dadc2a771256393506fb03862aa6c695
                .addData(data);
        }
            geo_json_dadc2a771256393506fb03862aa6c695_add({"features": [{"geometry": {"coordinates": [[-79.49986, 43.83871], [-79.502071, 43.837853], [-79.500148, 43.836124], [-79.499323, 43.832534], [-79.498699, 43.829193], [-79.498185, 43.827312], [-79.497678, 43.824112], [-79.499001, 43.821165], [-79.499131, 43.819961], [-79.491262, 43.821206], [-79.484858, 43.822144], [-79.484354, 43.820147], [-79.483929, 43.818274], [-79.483525, 43.816444], [-79.48316, 43.814118], [-79.483627, 43.812259], [-79.488189, 43.811377], [-79.492702, 43.810347], [-79.497367, 43.809708], [-79.500808, 43.80887], [-79.501032, 43.806255], [-79.500223, 43.802951], [-79.499334, 43.799172], [-79.498515, 43.796116], [-79.496816, 43.789141], [-79.496306, 43.7873], [-79.494723, 43.781775], [-79.504245, 43.779419], [-79.510792, 43.777917], [-79.512542, 43.77902]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_dadc2a771256393506fb03862aa6c695.bindTooltip(
                `<div>
                     10702 KEELE
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_dadc2a771256393506fb03862aa6c695.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_0b9e5e4b38a0f5408b0d26f80cbf13a6_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_0b9e5e4b38a0f5408b0d26f80cbf13a6_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_0b9e5e4b38a0f5408b0d26f80cbf13a6 = L.geoJson(null, {
                onEachFeature: geo_json_0b9e5e4b38a0f5408b0d26f80cbf13a6_onEachFeature,
            
                style: geo_json_0b9e5e4b38a0f5408b0d26f80cbf13a6_styler,
            ...{
}
        });

        function geo_json_0b9e5e4b38a0f5408b0d26f80cbf13a6_add (data) {
            geo_json_0b9e5e4b38a0f5408b0d26f80cbf13a6
                .addData(data);
        }
            geo_json_0b9e5e4b38a0f5408b0d26f80cbf13a6_add({"features": [{"geometry": {"coordinates": [[-79.415497, 43.782133], [-79.42011, 43.798695], [-79.422192, 43.807001], [-79.424299, 43.816215], [-79.425788, 43.822633], [-79.425631, 43.839979], [-79.431511, 43.847009], [-79.433174, 43.853739], [-79.434857, 43.860929], [-79.436922, 43.869916], [-79.439272, 43.88046], [-79.441653, 43.890312], [-79.442077, 43.894363]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_0b9e5e4b38a0f5408b0d26f80cbf13a6.bindTooltip(
                `<div>
                     60102 VIVA BLUE B
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_0b9e5e4b38a0f5408b0d26f80cbf13a6.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_0e08fd6f3215d109cd0376187c6ecf0d_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_0e08fd6f3215d109cd0376187c6ecf0d_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_0e08fd6f3215d109cd0376187c6ecf0d = L.geoJson(null, {
                onEachFeature: geo_json_0e08fd6f3215d109cd0376187c6ecf0d_onEachFeature,
            
                style: geo_json_0e08fd6f3215d109cd0376187c6ecf0d_styler,
            ...{
}
        });

        function geo_json_0e08fd6f3215d109cd0376187c6ecf0d_add (data) {
            geo_json_0e08fd6f3215d109cd0376187c6ecf0d
                .addData(data);
        }
            geo_json_0e08fd6f3215d109cd0376187c6ecf0d_add({"features": [{"geometry": {"coordinates": [[-79.442077, 43.894363], [-79.442618, 43.894221], [-79.44141, 43.888943], [-79.439322, 43.8795], [-79.436957, 43.869694], [-79.434594, 43.85951], [-79.432872, 43.852332], [-79.43136, 43.845794], [-79.425411, 43.840009], [-79.426035, 43.822276], [-79.424704, 43.816482], [-79.422566, 43.807246], [-79.420274, 43.798244], [-79.415497, 43.782133]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_0e08fd6f3215d109cd0376187c6ecf0d.bindTooltip(
                `<div>
                     60102 VIVA BLUE B
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_0e08fd6f3215d109cd0376187c6ecf0d.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_569255520949986d4d13fbb405c05448_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_569255520949986d4d13fbb405c05448_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_569255520949986d4d13fbb405c05448 = L.geoJson(null, {
                onEachFeature: geo_json_569255520949986d4d13fbb405c05448_onEachFeature,
            
                style: geo_json_569255520949986d4d13fbb405c05448_styler,
            ...{
}
        });

        function geo_json_569255520949986d4d13fbb405c05448_add (data) {
            geo_json_569255520949986d4d13fbb405c05448
                .addData(data);
        }
            geo_json_569255520949986d4d13fbb405c05448_add({"features": [{"geometry": {"coordinates": [[-79.425598, 43.840199], [-79.405542, 43.840071], [-79.397566, 43.840774], [-79.391193, 43.842282], [-79.386044, 43.843494], [-79.381701, 43.844456], [-79.377206, 43.845498], [-79.363611, 43.848661], [-79.35856, 43.849755], [-79.35123, 43.851287], [-79.339783, 43.853934], [-79.33418, 43.852009], [-79.331141, 43.848886], [-79.321604, 43.849974], [-79.311274, 43.853091], [-79.302829, 43.862761], [-79.292103, 43.865302], [-79.283868, 43.867217], [-79.267082, 43.871371], [-79.259326, 43.873945], [-79.243483, 43.87771], [-79.232901, 43.884803], [-79.231759, 43.88052]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_569255520949986d4d13fbb405c05448.bindTooltip(
                `<div>
                     60301 VIVA PURPLE A
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_569255520949986d4d13fbb405c05448.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_ccdb3667401f4e13947124627a9dd853_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_ccdb3667401f4e13947124627a9dd853_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_ccdb3667401f4e13947124627a9dd853 = L.geoJson(null, {
                onEachFeature: geo_json_ccdb3667401f4e13947124627a9dd853_onEachFeature,
            
                style: geo_json_ccdb3667401f4e13947124627a9dd853_styler,
            ...{
}
        });

        function geo_json_ccdb3667401f4e13947124627a9dd853_add (data) {
            geo_json_ccdb3667401f4e13947124627a9dd853
                .addData(data);
        }
            geo_json_ccdb3667401f4e13947124627a9dd853_add({"features": [{"geometry": {"coordinates": [[-79.231759, 43.88052], [-79.243027, 43.877991], [-79.260273, 43.873906], [-79.267589, 43.871474], [-79.285212, 43.86708], [-79.292544, 43.865408], [-79.303634, 43.86215], [-79.311311, 43.853503], [-79.322128, 43.85003], [-79.331565, 43.848882], [-79.334487, 43.851983], [-79.340128, 43.853922], [-79.352725, 43.851056], [-79.358978, 43.849739], [-79.363986, 43.848623], [-79.378708, 43.845323], [-79.383281, 43.844221], [-79.387352, 43.843223], [-79.392761, 43.84207], [-79.399105, 43.840549], [-79.405394, 43.84019], [-79.425598, 43.840199]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_ccdb3667401f4e13947124627a9dd853.bindTooltip(
                `<div>
                     60301 VIVA PURPLE A
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_ccdb3667401f4e13947124627a9dd853.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
    
        function geo_json_dd8cf5e37e11bf8b3c53b133e7625eb2_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "#A3248F", "opacity": 0.8, "weight": 3};
            }
        }

        function geo_json_dd8cf5e37e11bf8b3c53b133e7625eb2_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_dd8cf5e37e11bf8b3c53b133e7625eb2 = L.geoJson(null, {
                onEachFeature: geo_json_dd8cf5e37e11bf8b3c53b133e7625eb2_onEachFeature,
            
                style: geo_json_dd8cf5e37e11bf8b3c53b133e7625eb2_styler,
            ...{
}
        });

        function geo_json_dd8cf5e37e11bf8b3c53b133e7625eb2_add (data) {
            geo_json_dd8cf5e37e11bf8b3c53b133e7625eb2
                .addData(data);
        }
            geo_json_dd8cf5e37e11bf8b3c53b133e7625eb2_add({"features": [{"geometry": {"coordinates": [[-79.378708, 43.845323], [-79.383281, 43.844221], [-79.387352, 43.843223], [-79.392761, 43.84207], [-79.399105, 43.840549], [-79.405394, 43.84019], [-79.425598, 43.840199]], "type": "LineString"}, "id": "0", "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_dd8cf5e37e11bf8b3c53b133e7625eb2.bindTooltip(
                `<div>
                     60301 VIVA PURPLE A
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            geo_json_dd8cf5e37e11bf8b3c53b133e7625eb2.addTo(map_4173d0410d75dc81d269b1a032660cac);
        
</script>
</html>
