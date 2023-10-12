files challenge | Hard

this is file upload challenge but the name for file is random and the extention also not the same when you upload file 
the extention name take it from content of file so to solve this challenge 
send any png image and in first line(for the content of image) or second you will see png change it to php and send php code to take a web shell
The php code --> <?php system($_GET['cmd']); ?>

now you need to find the file after do some fuzzing you will see upload directory do fuzzing in the name for file what is will be like this 321.php so you will do fuzz in 321 until find your shell and you will end the challenge
