# Quick-Pass
Quick-Pass is a Python script that generates a strong  
password that can be used for just about anything.


## The importance of a strong password
I'm sure you've seen the occasional article or news report,  
where it's found that employees of "X" company or "Y" Corp  
had their security practices audited.

Janice in accounting used ***"password"*** as her password.  
hmmm, not bad Janice, but we need you to actually try.

John, well he's a clever boy. He stepped it up a notch:   
***"Password123"*** .  
I did say he was clever.  
And then there's Bill,

because there's always a Bill.

Bill's password is ***"Nr?r7]04Z\"*** .  
Wow Bill, that sounds like a decently strong password!  
Good Job Pal.

Bill gets a promotion and that new corner office hes been eyeing,

while John and Janice have to attend the super important mandatory  
meeting on why hiding your password under your family guy mouse pad,  
(Who still uses mouse pads) is a bad idea.  
We should all strive to be more like Bill.
However,  
being like Bill is hard.  
I get it.  
Coming up with a decent password on your own sucks, especially on the fly.  
Let Quick-Pass take care of that ickyness for you.


## Installation 
Getting Quick-Pass up and running is easy.

1. Open a terminal window and enter:  
`git clone https://github.com/syst3m-failur3/Quick-pass.git`  

2. Navigate to the cloned Quick-pass directory and enter:  
`sudo pip install .` 

3. We're Done!

## Running Quick-Pass
Quick-pass can generate passwords and passphrases.  

To generate a password with the default settings just type:  
`quick-pass password`  
That will give you a single 10 character password.

Simple enough, yeah?  
Our options for password generation are as follows:

- -l, --length  
    * The desired number of characters to be used.  
      (Defaults to 10)

- -a, --alphanumeric  
    * disallows the use of special characters.  
      (Is set to False by Default.)
    
- -q, --quantity  
    * The number of passwords to generate.  
      Defaults to 1)


Now to create a passphrase we enter:  
`quick-pass passphrase`  
This will give you a 4 word password with no spaces  
Our options for password generation are:

- -l, --length  
    * The desired number of characters to be used.  
      (Defaults to 10)
      
- -s, --spaces  
    * Include spaces in-between each word  
      (Defaults to False) 

- -q, --quantity  
    * The number of passwords to generate.  
      (Defaults to 1)

- -p, --path  
    * The path to wordlist.txt file  
      (If you'd like to use your own instead  
       instead of the provided diceware list)


## Password Tips
I thought i'd just toss in some helpful password  
and security tips, because i like you so much

- Password is not a good password.  
  Adding 123 doesn't make it better, i promise.
  
- Go ahead and turn on two-factor authentication.  
  [List of websites and whether or not they support 2FA. ](https://twofactorauth.org/)
  
- Don't neglect software updates!
  
- Never share your passwords with co-workers or really anyone for that matter.  
  [1 in 5 employees share their email passwords with coworkers](https://nakedsecurity.sophos.com/2018/09/11/yikes-1-in-5-employees-share-their-email-passwords-with-coworkers/)
  
- If you believe one of your accounts as been compromised,  
  don't hesitate,change your password, like right now, like now now  
  Why are you still reading this.
  
- Do not use the same passwords across all you accounts, if someone manages  
  to get that one password, they have access to everything,  
  and that's what we like to call, BAD.
  
- If you have a lot of long, complicated passwords to remember,  
  consider using a trusted password manager.  
  [How to evaluate a password manager?](https://security.stackexchange.com/questions/32536/how-to-evaluate-a-password-manager)  
      **A few password mangers to get you started.**  
      - [KeePass](https://keepass.info/)  
      - [BitWarden](https://bitwarden.com/)  
      - [Pass](https://www.passwordstore.org/)  
      - [1password](https://1password.com/)  


  

  










