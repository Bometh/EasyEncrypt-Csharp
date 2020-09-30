# EasyEncrypt-Csharp
A simple library to encrypt or decrypt a string

Adding Namespace
<pre><code class='language-cs'>
using Bometh.EasyEncrypt;
</code></pre>

Initializing the Object
<pre><code class='language-cs'>
EncryptDecrypt encdec = new EncryptDecrypt();
</code></pre>

Encrypting Password
<pre><code class='language-cs'>
string enc = encdec.Encrypt("testpassword");
</code></pre>

Decrypting Password
<pre><code class='language-cs'>
string dec = encdec.Decrypt("testpassword");
</code></pre>
