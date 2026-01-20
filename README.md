<div class="box">
แจกคอมมานซื้อของ By Pain

1. /give @s command_block
2. /give @s spawn_egg 1 51
3. /gamerule commandblockoutput false
4. /gamerule sendcommandfeedback false
5. /tickingarea add circle ~~~ 4 t
6. /scoreboard objectives add m dummy

Tag NPC เวลาไปยืนเฉพาะตัว:
tag @initiator add b

คำสั่งใน NPC ตัวซื้อ UI
playsound mob.villager.no @initiator[scores={m=..19}]
playsound note.harp @initiator[scores={m=..19}]
tellraw @initiator[scores={m=..19}] {"rawtext":[{"text":" §eคนขายของ§r: §cซื้อไม่สำเร็จ§r"}]}

(และต่อไป …)
</pre>
<pre class="box">
ใส่คอมมานด์จาก pastebin ของมึงตรงนี้
ก๊อปมาได้ทั้งก้อน
เว้นบรรทัดได้หมด
ไม่พัง
</pre>
