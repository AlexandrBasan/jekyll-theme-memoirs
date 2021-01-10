---
layout: page
title: Обратная связь
permalink: /contact
comments: false
---

<form action="https://formspree.io/{{site.email}}" method="POST">
<p class="mb-4">Хотите поговорить со мной? Я с радостью отвечу вам как только смогу!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Имя*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail Адрес*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Сообщение*" required></textarea>
<input class="btn btn-dark" type="submit" value="Отправить">

<p>Каждый день мне на почту поступает около 20-30 писем и я пытаюсь найти время, для того чтобы ответить на каждое. Прошу вас - не расстраивайтесь если вы не получили от меня ответа в течение нескольких часов. Вы всегда можете связаться со мной в социальных сетях и задать мне интересующие вас вопросы прямо там ;)</p>
</form>