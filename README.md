<html>

  

<script>
    function ping(){
       $.ajax({
          url: '216.58.10.14',
          success: function(result){
             alert('reply');
          },     
          error: function(result){
              alert('timeout/error');
          }
       });
    }
</script>
</html>
