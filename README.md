# Java-AES-Encryption-Decryption
    public static void main(String[] args) 
    {
        final String secretKey = "mypassword123@abc";
         
        String originalString = "This is ábcdqểrtyupy  6799 ~`!@#$%^&*()_+ {}[]\\|:;\"'<>,.?/";
        String encryptedString = AES.encrypt(originalString, secretKey) ;
        String decryptedString = AES.decrypt(encryptedString, secretKey) ;
         
        System.out.println("Original String: " + originalString);
        System.out.println("Encrypted String: " + encryptedString);
        System.out.println("Decrypted String: " + decryptedString);
    }
    #Result:
    Original String: This is ábcdqểrtyupy  6799 ~`!@#$%^&*()_+ {}[]\|:;"'<>,.?/
    Encrypted String: SJzg7U96V2tvHFMrMt3QRwxjvYcRqSD//f/Ghn5ilHVKvNEtb8T8lXMBZzmnBM1AC7pQwrQCUypYi3YMg+b5WQ==
    Decrypted String: This is ábcdqểrtyupy  6799 ~`!@#$%^&*()_+ {}[]\|:;"'<>,.?/
    
## Reference:
https://howtodoinjava.com/java/java-security/java-aes-encryption-example/
