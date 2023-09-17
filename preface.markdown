Önsöz
=======

Yazılımcılar fikirleri yazıya aktarırlar.

Bu yazılar önce sayılara ve bu sayılar diğer sayılara katıla katıla bir
şeylerin olmasını sağlarlar.

Yazılımcılar olarak, biz yazı editörlerini fikirlerimizi aklımızdan çıkarıp
bizim "yazılım" dediğimiz parçalara dönüştürmek için kullanırız. Tam zamanlı yazılımcılar yaşamlarını on binlerce saatlerini yazı editörleri ile 
cebelleşerek, şunları yapmaya çalışırız:

* Akıllarındaki ham yazıyı bilgisayara aktarmak.
* O yazılardaki hataları düzeltmek.
* O yazıyı probleme farklı bir açıdan bakmak için yeniden inşa etmek.
* Bir şey nasıl ve neden öyle yapıldı belgelemek.
* Ve diğer yazılımcılarla tüm bu şeyler hakkında ileteşebilmek için.

Vim is incredibly powerful out of the box, but it doesn't truly shine until you
take some time to customize it for your particular work, habits, and fingers.
This book will introduce you to Vimscript, the main programming language used to
customize Vim.  You'll be able to mold Vim into an editor suited to your own
personal text editing needs and make the rest of your time in Vim more
efficient.

Vim hiçbir şey yapılmasa dahi inanılmaz güçlüdür ama kendi işiniz, 
alışkanlıklarınız ve parmaklarınız için ayarlamak için biraz zaman 
harcayana kadar tamamen parlamaz.
Bu kitap sizi Vim'i ayarlamak için kullanılan ana programlama dili olan 
Vimscript ile tanıştıracak.
Vim'i keyfinize göre kalıba döküp kendi  yazı editleme ihtiyaçlarınıza 
uygun ve çok daha verimli hale getirebileceksiniz


Along the way I'll also mention things that aren't strictly about Vimscript, but
are more about learning and being more efficient in general.  Vimscript isn't
going to help you much if you wind up fiddling with your editor all day instead
of working, so it's important to strike a balance.

The style of this book is a bit different from most other books about
programming languages.  Instead of simply presenting you with facts about how
Vimscript works, it guides you through typing in commands to see what they do.

Sometimes the book will lead you into dead ends before explaining the "right
way" to solve a problem.  Most other books don't do this, or only mention the
sticky issues *after* showing you the solution.  This isn't how things typically
happen in the real world, though.  Often you'll be writing a quick piece of
Vimscript and run into a quirk of the language that you'll need to figure out.
By stepping through this process in the book instead of glossing over it I hope
to get you used to dealing with Vimscript's peculiarities so you're ready when
you find edge cases of your own.  Practice makes perfect.

Each chapter of the book focuses on a single topic.  They're short but packed
with information, so don't just skim them.  If you really want to get the most
out of this book you need to actually type in all of the commands.  You may
already be an experienced programmer who's used to reading code and
understanding it straight away.  If so: it doesn't matter.  Learning Vim and
Vimscript is a different experience from learning a normal programming language.

You need to **type in *all* the commands.**

You need to **do *all* the exercises.**

There are two reasons this is so important.  First, Vimscript is old and has
a lot of dusty corners and twisty hallways.  One configuration option can change
how the entire language works.  By typing *every* command in *every* lesson and
doing *every* exercise you'll discover problems with your Vim build or
configuration on the simpler commands, where they'll be easier to diagnose and
fix.

Second, Vimscript *is* Vim.  To save a file in Vim, you type `:write` (or `:w`
for short) and press return.  To save a file in a Vimscript, you use `write`.
Many of the Vimscript commands you'll learn can be used in your day-to-day
editing as well, but they're only helpful if they're in your muscle memory,
which simply doesn't happen from just reading.

I hope you'll find this book useful.  It's *not* meant to be a comprehensive
guide to Vimscript.  It's meant to get you comfortable enough with the language
to mold Vim to your taste, write some simple plugins for other users, read other
people's code (with regular side-trips to `:help`), and recognize some of the
common pitfalls.

Good luck!
