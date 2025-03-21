# December-Batch
This repository uses to exchange code among the team for collaobration and version control
$('form').submit(function(event) {
  event.preventDefault(); // Prevents the default form submission
  // Custom logic, such as AJAX submission
  $.ajax({
    type: 'POST',
    url: 'your-url',
    data: $('form').serialize(),
    success: function(response) {
      // Handle the response
    }
  });
