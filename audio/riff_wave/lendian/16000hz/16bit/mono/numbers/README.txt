for number in {0..128}; do echo $number; (echo $number | text2wave -otype wav -o $number.wav -); done
