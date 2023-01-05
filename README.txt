■ JQuery로 class를 잡아서 그 내용을 바꾸려면
<span class="badge bg-light">Dark 🔄</span>

$('.badge').html('Light 🔄')

■ JQuery로 id를 잡아서 특정 클래스의 이름을 더 길게 하고 싶으면
<button id="login">로그인</button>
$('#login').on('click', function() {
  $('.black-bg').addClass('show-modal');
 })
