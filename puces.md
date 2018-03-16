= Plusieurs solution pour faire des puces =

== background-image ==

#tinymce ul li:before, 
.site-content-page ul li:before {
    display: block;
    position: absolute;
    left: 0;
    vertical-align: middle;
    width: 14px;
    height: 13px;
    content: '>';
    background: url(../images/puce.png) no-repeat center;
}


#tinymce ul li, 
.site-content-page ul li {
    position: relative;
    padding-left: 19px;
    padding-top: 3px;
}



