<p align="center">
<img src="https://i.imgur.com/uxaU4CG.png" height="30%" width="60%" alt="Kali Linux Logo"/>
</p>

<h1>Encrypting files with ccrypt on Kali Linux</h1>
This tutorial outlines the implementation of encrypting files on Kali Linux.<br />


<h2>Environments and Technologies Used</h2>

- Oracle VirtualBox (Virtual Machines/Computer)
- Kali Linux Shell

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>Encryption Steps</h2>

<p>
<img src="https://imgur.com/4b4Advn.png" height="80%" width="80%" alt="Encryption Steps"/>
</p>
<p>
Encryption

1. Run the following command in the Kali Linux command prompt. (ccrypt encryptiontest)
2. When prompted to enter an encryption key, type 1827390, and then press Enter. When prompted to reenter the encryption key, type 1827390, and then press Enter.
3. Now view your file in the directory again. Run ls to list the files.
4. Run the following command to open the cpt file. (nano encryptiontest.cpt)

</p>
<br />

<p>
<img src="https://imgur.com/XcR4sgE.png" height="80%" width="80%" alt="Encryption Display Steps"/>
</p>
<p>
The displayed content is cyphertext: a string of random letters, numbers, and symbols representing the encrypted content.

1. Press Ctrl+X to exit the editor.
2. In the command line, run the following command to display the content od the encrypted file. (ccat encryptiontest.cpt)
3. When prompted to enter the decryption key, type 1827390 or any other key that you used for encryption, and then press Enter.

You will now be able to see the actual content of the file.
</p>
<br />

