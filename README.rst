Octopress Theme for Pelican
===========================

By `Maurizio Sambati`_ and others.  See the original `repository`_ for the full README.  

Changes made
-------------------

#.  Edited static/css/main.css and changed the body element's "max-width" attribute to 870px instead of 1200px  (body{...;max-width:870px;...).  
#.  Edited static/js/octopress.js and commented-out code that toggled the sidebar on/off.  It is now off permanently.  
#.  Edited templates/base.html to give the body element class="collapse-sidebar" so that it would always be in collapsed mode.  This makes the footer appear permanently.  The commented-out javascript was previously responsible for adding/removing this class.  
#.  Removed sidebar remnant from static/css/main.css by changing the sidebar's margin-right to 0px (.collapse-sidebar #content{margin-right:0px}).  



.. _`repository`: http://github.com/duilio/pelican-octopress-theme
.. _`Maurizio Sambati`: https://github.com/duilio
