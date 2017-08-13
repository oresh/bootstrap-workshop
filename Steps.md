## HTML
    block elements
        div, section, header, footer, article, nav
    text elements
        h1,h2,h3,h4,h5,p,em, i, b, small, blockquote
    utility elements
        span, ul, ol, li, 
    classes, ids, class stacking
    form
        input, textarea, button
    attributes

## Bootstrap 3.3

https://v4-alpha.getbootstrap.com/examples/cover/#
https://v4-alpha.getbootstrap.com/examples/blog/
https://v4-alpha.getbootstrap.com/examples/justified-nav/

Themes:
https://blackrockdigital.github.io/startbootstrap-creative/
https://blackrockdigital.github.io/startbootstrap-landing-page/
https://blackrockdigital.github.io/startbootstrap-sb-admin-2/pages/index.html

### Getting started
    Basic info
    What is Bootstrap, and why it's cool
    Download
    Less or Sass
    JavaScript
    Options

### Overview
    Mobile first
    Normalize.css
    container, container-fluid, 

### Layout
    Overview    
    Grid
        xs sm md lg
        clearfix visible-xs-block
        -offset-*
        push, pull

### Typography
    Headings
        h1-h5
    Body copy
        .lead
    Inline text elements
        mark(highlight), del == s, ins, u, small, strong, em
    Alignment classes
        text-left text-center text-right text-justify text-nowrap
    Transformation classes
        text-lowercase text-uppercase text-capitalize
    Blockquotes
        <blockquote>
    Lists
        ul, ol, li, list-unstyled, list-inline

### Code
    skip

### Tables
    Basic example
        .table
    Striped rows
        .table-striped
    Bordered table
        .table-bordered
    Hover rows
        .table-hover
    Condensed table
        .table-condensed
    Contextual classes
        .active .success .info .warning .danger ( on row )
    Responsive tables
        .table-responsive (wrapper over .table)

### Forms
    Basic example
        .form-group, .control-label, .form-control, .checkbox
    Inline form
        .form-inline
        .input-group - skip
    Horizontal form
        .form-horizontal
    Supported controls
        supports: text, password, datetime, datetime-local, date, month, time, week, number, email, url, search, tel, and color.
    Static control
        skip
    Focus state
        skip
    Disabled state
        disabled attr.
    Readonly state
        readonly attr
    Help text
        .help-block
    Validation states
        .has-warning, .has-error, or .has-success on .form-group
        has-success has-error has-warning on checkbox wrapper
    Control sizing
        .input-lg, .input-sm on .form-control
        .form-group-lg, form-group-sm on form-group
    
### Buttons
    Button tags
        a, button, input
    Options
        default primary success info warning danger link
    Sizes
        lg sm xs btn-block
    Active state
        .active
    Disabled state
        disabled="disabled" or .disabled for a

### Images
    <img src="..." class="img-responsive" alt="Responsive image">

### Helper classes
    ——
    Contextual colors
    Contextual backgrounds
    Close icon
    Carets
    Quick floats
        pull-left pull-right
    Center content blocks
        center-block
    Clearfix
        .clearfix
    Showing and hiding content
        .show .hidden
    Screen reader and keyboard navigation content
    Image replacement
    
### Responsive utilities
    .hidden-xs/sm/md/lg .visible-xs-* (block, inline, inline-block)

### Sass
    https://github.com/twbs/bootstrap-sass



## Bootstrap components

    Glyphicons
        <span class="glyphicon glyphicon-search" aria-hidden="true"></span>
    Dropdowns
        (start only)
    Button groups
        (start only)
    Button dropdowns
        (start only)
    Input groups
        skip
    Navs
        Tabs
        Pills
        Using dropdowns
    Navbar
        Default navbar
        Forms
        Buttons
        Text
        Non-nav links
        Component alignment
        Static top
    Breadcrumbs
        <ol class="breadcrumb">
        <li><a href="#">Home</a></li>
        <li><a href="#">Library</a></li>
        <li class="active">Data</li>
        </ol>
    Pagination
        <ul class="pagination">
            <li>
    Labels
        <span class="label label-default">New</span></h3>
    Badges
        <span class="badge">42</span>
    Jumbotron
        <div class="jumbotron">
    Page header
        <div class="page-header">
    Thumbnails
        <a href="#" class="thumbnail"> / <div class="thumbnail">
            <img src="..." alt="...">
        </a>
    Alerts
        <div class="alert alert-warning" role="alert">
            ... <a href="#" class="alert-link">...</a>
        </div>
    Progress bars
        <div class="progress">
            <div class="progress-bar" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%;">
            </div>
        </div>
    Media object
        skip
    List group
        <ul class="list-group">
            <li class="list-group-item">Cras justo odio</li>
        </ul>
    Panels
        <div class="panel panel-default">
            <div class="panel-heading">Panel heading without title</div>
            <div class="panel-body">
                Basic panel example
            </div>
        </div>
    Responsive embed
        <div class="embed-responsive embed-responsive-16by9">
        <iframe class="embed-responsive-item" src="..."></iframe>
        </div>
        <div class="embed-responsive embed-responsive-4by3">
        <iframe class="embed-responsive-item" src="..."></iframe>
        </div>
    Wells
        <div class="well">...</div>


## Bootstrap JavaScript

    Transitions
        default
    Modal
        <button type="button" class="btn btn-primary btn-lg" data-toggle="modal" data-target="#myModal">
            Launch demo modal
        </button>
        ... Modal
    Dropdown
        <button id="dLabel" type="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
        <ul class="dropdown-menu" aria-labelledby="dLabel">
    Scrollspy
        skip
    Tab
        <ul class="nav nav-tabs" role="tablist">
            <li role="presentation" class="active"><a href="#home" aria-controls="home" role="tab" data-toggle="tab">Home</a></li>
        </ul>
        <div class="tab-content">
            <div role="tabpanel" class="tab-pane active" id="home">...</div>
    Tooltip
        data-toggle="tooltip" data-placement="left" title="Tooltip on left"
    Popover
        data-toggle="popover" title="Popover title" data-content="And here's some amazing content. It's very engaging. Right?"
    Alert
        <button type="button" class="close" data-dismiss="alert" aria-label="Close">
            <span aria-hidden="true">&times;</span>
        </button>
    Button
        skip
    Collapse
        <a class="btn btn-primary" role="button" data-toggle="collapse" href="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
            Link with href
        </a>
        <div class="collapse" id="collapseExample">
    Carousel
        show
    Affix
        skip


## Twig

https://twig.symfony.com/doc/2.x/templates.html

### Overview
    {{ }}
    {% %}
    {# ... #}
    {% if something %} {% endif %}
    {% for i in array %} {% endfor %}
    ~

### Attrs
    {{ foo.bar }}
    {{ foo['bar'] }}
    {{ attribute(foo, 'data-foo') }}

### Globals
    {% set foo = 'foo' %}
    {% set foo = [1, 2] %}
    {% set foo = {'foo': 'bar'} %}

### Filters
    capitalize
        'text'|capitalize
    lower
        {{ 'WELCOME'|lower }}
     batch
        array|batch(3, 'No item')
        {% for row in items|batch(3, 'No item') %}
        takes items by 3, if <3 left, returns 'no item'
    date
        {{ post.published_at|date("m/d/Y") }}
        {{ post.published_at|date("m/d/Y", "Europe/Paris") }}
        from here: http://php.net/manual/en/function.date.php
    date_modify
        {{ post.published_at|date_modify("+1 day")|date("m/d/Y") }}
        from here: http://php.net/strtotime
    default
        {{ var|default('var is not defined') }}
    first
        array|first
        object|first
        string|first
    last
        as first
    format
        {{ "I like %s and %s."|format(foo, "bar") }}
        from here: http://php.net/sprintf
    join
        {{ [1, 2, 3]|join }}
        {{ [1, 2, 3]|join('|') }}
    keys
        ? {% for key in array|keys %}
    length
        ? array,object,string|length
    merge
        {% set values = [1, 2] %}
        {% set values = values|merge(['apple', 'orange']) %}

### Functions

    cycle
        {{ cycle(fruits, i) }}
    dump
        {{ dump(user) }}
    max
        {{ max(1, 3, 2) }}
        {{ max([1, 3, 2]) }}
    min
        {{ min(1, 3, 2) }}
        {{ min([1, 3, 2]) }}
    random
        {{ random(['apple', 'orange', 'citrus']) }} {# example output: orange #}
        {{ random('ABC') }}                         {# example output: C #}
        {{ random() }}                              {# example output: 15386094 (works as the native PHP mt_rand function) #}
        {{ random(5) }}                             {# example output: 3 #}

### Control Structure

Template Inheritance
    {% block head %}
        <link rel="stylesheet" href="style.css" />
        <title>{% block title %}{% endblock %} - My Webpage</title>
    {% endblock %}

    {% extends "base.html" %}
    {% block title %}Index{% endblock %}