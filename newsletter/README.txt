   for the "check out our newsletter" button to appear in every page of our website,add this in head tag
   
   
   <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.1/dist/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>


and this in body tag 

<!-- Button to Trigger the Modal -->
<button type="button" class="btn btn-primary" data-toggle="modal" data-target="#newsletterModal">
    Check out our newsletters
</button>

<!-- Include Modal Content -->
<div id="modalContent"></div>