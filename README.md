
#Intro to the song
introjonas = "C:/Users/leah_torres/Documents/Audacity/intro.wav"
space = "C:/Users/leah_torres/Documents/Audacity/space.wav"
live_loop :bass do
  sample :bass_trance_c, amp: 0.5
  sleep 1
end
live_loop :introjonas do
  sample introjonas, amp: 2
  sleep 7
end
=begin
live_loop :bass do
  stop
end
live_loop :introjonas do
  stop
end
=end
