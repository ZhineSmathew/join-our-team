-   About Me
- Myself, Shine S. Mathew, graduated with a bachelor's degree in bachelor of computer application from MGU in 2019 Passout.I am currently working at Vijay Software as a software engineer. completed 1.6 years in Web development with PHP, Laravel, MySQL, and AWS experiences. along with that pursuit of MCA from ignou in distances. I look forward to advancing my career as a skilled back-end developer and Flutter developer
- OS - Windows & linux | Visual studio code
-   Social Profile
- github https://github.com/ZhineSmathew
- linkedin https://www.linkedin.com/in/shine-s-profile/
- resume  https://resume.io/r/8gkhIxusL
-  real stuff
-  Laravel,PHP,Wordpress
-  Write a function that takes a number and returns an array of its digits
-  function numtoarray($val){
    $strval=(string) $val;
    $strval=str_split($strval);
    print_r ($strval);
   }
   return numtoarray(10001);
  - Write function that translates a text to Pig Latin and back. English is translated to Pig Latin by taking the first letter of every word, moving it to the end of the word and adding ‘ay’. “Join with yellowfish” becomes “oinjay ithway ellowfishyay
- function wordtopiglatin($text){
    $words= explode(' ',$text);
    foreach($words as $word){
        $firstLett = substr($word,0,1);
        $balword = substr($word,1);
        if(preg_match('/^[aeiou]/i',$firstLett)){
            $finaloutput= $word . 'way';
            echo $finaloutput;
        }
        else{
            $finaloutput = $balword . $firstLett. 'ay';
            echo $finaloutput;
        }
    }
}
return wordtopiglatin("YellowFish");
- Write a function that rotates an array by k elements. For example [1,2,3,4,5,6] rotated by two becomes [3,4,5,6,1,2]. Try solving this without creating a copy of the array
- function rotarray($arr){
    $reverseArray=implode('',$arr);
    $firstval = substr($reverseArray,2);
    $secval = substr($reverseArray,0,2);
    echo $firstval.$secval;
}
$arr = array(1,2,3,4,5,6,7);
return rotarray($arr);
