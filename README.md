fakeScroll
========

### [DEMO PAGE](http://yaireo.github.io/fakescroll)

Very lightweight & robust custom-looking scrollbar script.


## Example markup:

    <div class="foo">
        ...
        ...
        ...
    </div>

## Initializing:

    document.querySelector('.foo').fakeScroll();

## The above will transform into this:

    <div class="foo">
        <div class="fakeScroll__wrap">
            <div class="fakeScroll__content">
                ...
                ...
                ...
            </div>
        </div>
        <div class="fakeScroll__bar"></div>
    </div>



## Settings

Name                | Type            | Default     | Info
------------------- | ----------      | ----------- | --------------------------------------------------------------------------
classname           | String          | ""          | Class name which is added to the ".fakeScrollBar" element
offset              | String          | 0 0 0 0     | scroll offset
track               | Boolean/String  | false       | enable track events. use "smooth" for smooth "jumping"