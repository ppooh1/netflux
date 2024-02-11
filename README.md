# Netflux

## Streaming Features 
### หน้าบ้าน 
* Login/Register
* Select Movie genre/category
* Search Function
  * by Movie name, cast, Writer/Director, or keywords
* Movie Control : Video player
* Functions (Playback, Play forward, Speed, Skip Intro, Stop, Resume)
* Quality Selection(360p, 720p, 1080p)
* Watchlist/Add to Favorites:
* Notification

### หลังบ้าน
* Login Admin
* Add Category
  * Add/Edit Movie
   * Tags
   * Genre
   * Movie name
   * Start time (Ex. 1:30) เพื่อใช้ Skip intro
   * Writer/Director
   * Cast
* User Control (Ban/Unban/Change info/ Check information)

### Use Case
* User Authentication
  * 1.) Login
    * 1.1) กรอก email
    * 1.2) กรอก password
    * 1.3) กดปุ่ม login
      
![auth](https://media.canva.com/1/image-resize/1/2400_1560_100_PNG_F/czM6Ly9tZWRpYS1wcml2YXRlLmNhbnZhLmNvbS9MMjZuZy9NQUY3NTBMMjZuZy8xL3AucG5n?osig=AAAAAAAAAAAAAAAAAAAAAP3zsh2ZFmMOZrZPpNZxFVptdsZWnBNyv8KBSdTlO2pQ&exp=1707699774&x-canva-quality=screen_3x&csig=AAAAAAAAAAAAAAAAAAAAAP0tOenhMnuID9buKMiKzZBQL4V4kgpvr1JLiSDeUWaG)

  * 2.) Register
    * 2.1) กรอก email
    * 2.2) กรอก password
    * 2.3) กรอก confirm password
    * 2.4) กดปุ่มสมัครสมาชิก

![register](https://media.canva.com/1/image-resize/1/2400_1560_100_PNG_F/czM6Ly9tZWRpYS1wcml2YXRlLmNhbnZhLmNvbS9heWlZSS9NQUY3NXlheWlZSS8xL3AucG5n?osig=AAAAAAAAAAAAAAAAAAAAAFi34r7ByxQL8t3t04OMDWWhhcW6BeNnpfQfNS4u_4s9&exp=1707698761&x-canva-quality=screen_3x&csig=AAAAAAAAAAAAAAAAAAAAAMyMk1IZR-diSETaGzQfKnNON7dzxU7guBkH9OGmzUw4)

* View Category
  * 3.) เลือก Category(เช่นเลือกตาม genre , tags , etc.)
    * 3.1) เลือก content ที่ต้องการโดยการกด
    * 3.2) กดเข้าไปใน content page แล้วกดเล่น

![viewcategory](https://media.canva.com/1/image-resize/1/960_539_100_PNG_F/czM6Ly9tZWRpYS1wcml2YXRlLmNhbnZhLmNvbS9qQXhZby9NQUY3NkJqQXhZby8xL3AucG5n?osig=AAAAAAAAAAAAAAAAAAAAACl8fzn6Pt9Y5c51xJ7AqgUI7jED3ikM29SW2tMdZDFf&exp=1707700556&x-canva-quality=screen_2x&csig=AAAAAAAAAAAAAAAAAAAAAG28a5Y8vb5yZhf7wQvKvIeTNrZMCvtpjUmnpKr4U4F2)

![genre](https://media.canva.com/1/image-resize/1/2400_1560_100_PNG_F/czM6Ly9tZWRpYS1wcml2YXRlLmNhbnZhLmNvbS8tNktpWS9NQUY3NTAtNktpWS8xL3AucG5n?osig=AAAAAAAAAAAAAAAAAAAAAK0VZZxeNEdKTRw5Rwlc4wuvtLzMClV9SK3iibhV0yFp&exp=1707699628&x-canva-quality=screen_3x&csig=AAAAAAAAAAAAAAAAAAAAAGazfgWRQda7WodPpxK4yAvPBjRNaHQTsOyoZ1qon514)

* View Content เลือกคอนเท้นต์
  * 4.) หลังจากล็อคอินมาแล้ว จะมีหนังให้เลือกที่หน้าหลัก 
  * 4.1) ผู้ใช้สามารถเลือกคลิป / หนังที่จะดูได้ 
  * 4.2) ผู้ใช้ทำการกดเลือกหนังที่จะดู จากนั้นตัวแอพจะเปิด video มาให้ดู

![viewcontent](https://media.canva.com/1/image-resize/1/2400_1560_100_PNG_F/czM6Ly9tZWRpYS1wcml2YXRlLmNhbnZhLmNvbS9fTzhISS9NQUY3NS1fTzhISS8xL3AucG5n?osig=AAAAAAAAAAAAAAAAAAAAABsXUvmuTEGue7bdiOWaCt2MmJsz2-eOvgMpDnb9yn_y&exp=1707698926&x-canva-quality=screen_3x&csig=AAAAAAAAAAAAAAAAAAAAAGCsz8_Bdl2qLLaVl-84uy8h9rQ0irDkdEBZRmm8nz9w)

* Video player เล่นวิดิโอ
  * 5.) ระหว่างหนังกำลังเล่น ผู้ใช้สามารถเลือกที่จะ skip intro หรือปรับ speed ปรับ quality , play back , resume , play forward และสามารถหยุดเล่นและกลับไปหน้าหลักได้
  * 5.1) หลังจากดูหนังจนจบ จะมีให้เลือก Recommended (หนัง/คลิปแนะนำ) หรือผู้ใช้สามารถกลับไปหน้าหลักได้

 ![videoplayer](https://media.canva.com/1/image-resize/1/2400_1560_100_PNG_F/czM6Ly9tZWRpYS1wcml2YXRlLmNhbnZhLmNvbS9lcVVOWS9NQUY3NV9lcVVOWS8xL3AucG5n?osig=AAAAAAAAAAAAAAAAAAAAAFlZkxedvmu7rLc1BtWy_uwZexkfKJv1EeN7Y5pIC7Nf&exp=1707697207&x-canva-quality=screen_3x&csig=AAAAAAAAAAAAAAAAAAAAALZrITsoeFbUzFOtuRNqy08jM38CAI9yXLcBpgRJr208)

widget ที่ใช้
* textfield
* dropdown
* button
* iconbutton
* imagebutton
* row
* collumn
* stack
* container
