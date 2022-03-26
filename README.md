## Learning Vue JS

## Lession 1: Getting Star
I love vue => Code Vuejs trong template của VueJS (JS trong DOM HTML)
Vue Tạo ra đối tượng và quản lý đối tượng đó DOM HTML
Directive : Chỉ thị trong Vue
Shorthand : @keyup
SỰ KIÊN CHỈ THỊ :
sự kiện thì dùng : target trong func event để lấy tương ứng
v-on:input  
v-on:click
v-on:mousemove
event.stopPropagation :Dừng diễn biến sự kiện move

## Lession 2: Using VueJS to Interact with the DOM

<ul>
    <li>Vue ko có đoạn mã sinh thêm , nó dùng HTML base template  :cho phép ràng buộc dữ liệu ,giúp minh bạch</li>
</ul>
<li>Vue ko có đoạn mã sinh thêm , nó dùng HTML base template  :cho phép ràng buộc dữ liệu ,giúp minh bạch</li>
<li>Vue làm việc với thẻ Tag của HTML chứ ko truy cập vào Attribute HTML được => dùng v-bind để bind dữ liệu</li>
<li>v-bind:href </li>
<li>v-once : giử lại các giá trị lúc chưa thay đổi và đã thay đổi
v-html : render các chuỗi thẻ HTML ra DOM (vì dữ liệu truyền qua HTML  trong Vue đều ở dạng text)</li>
<h5>Sự kiện bàn phím</h5>
<ul>
    <li>v-on:keyup : có bổ sung modifier sau khi keyup </li>
    <li>Có thể viết JS trong bind {{sử dụng như JS}}</li>
    <li>Cách bind v-on:input - Cách bind : sử dụng v-model </li>
  
</ul>

## Computed,Watch
<ul>
  <li>Khi gọi 1 function trong vue js , thì tất cả function sẻ đc gọi theo chờ sẳn nhưng chưa hẳn in ra kết quả . (Mục đích cho nhanh của Vue JS ) ==> <b>Computed (Properti)</b></li>
    <li>Computed chạy giống như 1 func ,nhưng khi gọi ko cần phải gọi hàm như v ()</li>
    <li><b>Watch </b>Theo dỏi 1 biến.Khi 1 biến nào đó có thay đổi thì . Watch sẻ hoạt động</li>
</ul>

## Shorthand
<ul>
  <li>Khi gọi 1 function trong vue js , thì tất cả function sẻ đc gọi theo chờ sẳn nhưng chưa hẳn in ra kết quả . (Mục đích cho nhanh của Vue JS ) ==> <b>Computed (Properti)</b></li>
    <li>Computed chạy giống như 1 func ,nhưng khi gọi ko cần phải gọi hàm như v ()</li>
    <li><b>Watch </b>Theo dỏi 1 biến.Khi 1 biến nào đó có thay đổi thì . Watch sẻ hoạt động</li>
    <li>Quản lý Class qua :class={do:quanlido} <=> do:true</li>
    <li>Quản lý Name qua :class=color</li>

</ul>

## Lession 3: Using Conditionals and Rendering Array List
<h1>Conditionals</h1>
<ul>
  <li>v-if=  xoá đi element DOM</li>
  <li>v-else</li>
  <li>Alternative : dùng nhiều if</li>
</ul>
<h1>Detach(tách ra : thêm thuộc tính mới vào HTML) - v-show</h1>
<ul>
  <li>v-if= </li>
  <li>v-else</li>
  <li>v-show Display:none => <b>v-show</b>Ko áp dụng cho teamplate</li>
</ul>

  <h1>Render List</h1>
  <ul>
    <li>v-for</li>
    <li>v-for="(user ,index) in users"</li>
    <li>v-for có thể sử dụng alternative => template</li>
    <li><b>Lặp qua Oject</b></li>
    <li>Looping through a List of Numbers</li>
</ul>
<h1>Keep track : theo dỏi</h1>
<p>Khi for thì sẻ sinh ra Unique  key assign và index</p>
<ul>
    <li>unique                  index</li> 
    <li> đasadsadfa                 0</li>
   <li> dssd                        1</li>
    <li>...                           ...</li>
</ul>

## Lession 4:Project 1

## Lession 5: Understanding the VueJS Instance (cách hoạt động, vòng đời,befor,after)

## Lession 6: Moving to a real Development Workfolow (điều khiển vòng chạy)

## Lession 7: An Introduction to Component

## Lession 8: Communicating between Components

## Lession 9: Advanced Component Usage

## Lession 10: Project 2

## Lession 11: Handling User input with Form

## Lession 12: Using and Creating Directive

## Lession 13: Improving your app with Filters and

## Lession 14 : Adding Animation and Transition

## Lession 15: Connecting to Server via Http

## Lession 16 : Routing in a VueJS Application

## Lession 17: Better State Management with VueJS (quản lý)

## Lession 18: Final Project

## Lession 19: Deloying a Vue JS Application
