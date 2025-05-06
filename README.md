# cse539-project-3-diffie-hellman-and-encryption-projectsolved
**TO GET THIS SOLUTION VISIT:** [CSE539 Project 3-Diffie-Hellman and Encryption ProjectSolved](https://www.ankitcodinghub.com/product/cse539-project-3-diffie-hellman-and-encryption-projectsolved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96098&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE539 Project 3-Diffie-Hellman and Encryption ProjectSolved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
&nbsp;

Purpose

In this project, you will gain experience working with existing libraries to perform encryption using a 256-bit key. To generate the key, you will implement a part of the Diffie-Hellman algorithm. In doing so, you will also learn how to work with very large numbers that are too large to store in a standard data type such as integer or long.

Objectives

Students will be able to:

<ul>
<li>● &nbsp;Implement the Diffie-Hellman Key Exchange.</li>
<li>● &nbsp;Employ existing algorithms to encrypt and decrypt data.</li>
<li>● &nbsp;Apply number theory concepts to solve real-world problems.
Technology Requirements

TPerocghrnaomlomgyinrgeaqsusiriegmnmenetnstswsilhl boeuldfobuendonethuesicnlags.sNGETitHCuobreR3E.A1.DWMhEile(Cyliocuk coarncowpryitethyeoluinrkcobdeelow) hotntpsa://Wgitihnudbo.cwoms/oGrivMeTahcanmksaAclwhianyes/,CtShEe-5a3u9t-oAgprpaliedde-rCwrypilltotgersatphyyo-u20r2c1o-Fdaell-oBn Ubuntu 18.04. It is highly recommended to create a Virtual Machine for writing your assignments.

Information on how to install the .NET Core SDK on Ubuntu can be found on Microsoft’s website: ​Install .NET Core SDK or .NET Core Runtime on Debian

You can create a new project using this command: dotnet new console –output project_name You can also run your project by going into your project directory and using: dotnet run
</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Directions

The first part of this assignment involves the creation of a 256-bit key for performing encryption. You will be implementing the Diffie-Hellman key exchange protocol. Typically, this protocol involves two parties concurrently sharing values and generating a key. In this assignment, you will be given all necessary values immediately and will not be required to send values over any channel. In this way, you can perform calculations as a single party.

Here is a brief reminder of how Diffie-Hellman works:

<ol>
<li>1) &nbsp;Alice and Bob agree on values for g and N.</li>
<li>2) &nbsp;Alice randomly picks x and Bob randomly picks y.</li>
<li>3) &nbsp;Alice computes gx​ ​mod N and sends it to Bob (call this gx).</li>
<li>4) &nbsp;Bob computes gy​ ​mod N and sends it to Alice (call this gy).</li>
<li>5) &nbsp;Alice computes (gy)x​ ​mod N, and Bob computes (gx)y​ ​mod N. These two values are
equivalent and are the key.
</li>
</ol>
The encryption algorithm you will be using in this project is AES (i.e., Rijndael encryption). You can use the AES class in the C# System.Security.Cryptography namespace. You will be using the 256-bit key mode. In order to perform the encryption, you will also need an IV. In this exercise, you will employ a 128-bit IV passed via command line in hex. Here is the list of values you will receive from the command line arguments, in order:

<ol>
<li>1) &nbsp;128-bit IV in hex</li>
<li>2) &nbsp;g_e in base 10</li>
<li>3) &nbsp;g_c in base 10</li>
<li>4) &nbsp;N_e in base 10</li>
<li>5) &nbsp;N_c in base 10</li>
<li>6) &nbsp;xinbase10</li>
<li>7) &nbsp;gy​​ modNinbase10</li>
<li>8) &nbsp;An encrypted message C in hex</li>
<li>9) &nbsp;A plaintext message P as a string</li>
</ol>
Hint: You may not need all of these values to perform the computations.

Note: To facilitate debugging, the values for g and N are given as a pair of values, the exponent (e) and the constant (c). You can calculate the value for either using the formula 2e​ ​- c. For example, if you were given g_e = 250, g_c = 207, N_e = 256, and N_c = 189, your values for g and N should be as follows:

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
g= 1809251394333065553493296640760748560207343510400633813116524750123642 650417

N= 1157920892373161954235709850086879078532699846656405640394575840079131 29639747

To perform these calculations without encountering an overflow, you ​cannot​ use int (32-bit), long (64-bit), or decimal (96-bit). Instead, you must make use of C#’s BigInteger struct, which supports any arbitrarily long integer.

After calculating the key, your program must perform a decryption of the given ciphertext bytes and an encryption of the given plaintext string. Your program should output these values as a comma separated pair (the decrypted text followed by the encrypted bytes). Here is a full example:

Command: dotnet run “A2 2D 93 61 7F DC 0D 8E C6 3E A7 74 51 1B 24 B2” 251 465 255 1311 2101864342 8995936589171851885163650660432521853327227178155593274584417851704581 358902 “F2 2C 95 FC 6B 98 BE 40 AE AD 9C 07 20 3B B3 9F F8 2F 6D 2D 69 D6 5D 40 0A 75 45 80 45 F2 DE C8 6E C0 FF 33 A4 97 8A AF 4A CD 6E 50 86 AA 3E DF” AfYw7Z6RzU9ZaGUloPhH3QpfA1AXWxnCGAXAwk3f6MoTx

Expected output: uUNX8P03U3J91XsjCqOJ0LVqt4I4B2ZqEBfX1gCGBH4hH,3D E9 B7 31 42 D7 54 D8 96 12 C9 97 01 12 78 F7 A2 4F 69 1A FF F4 42 99 13 A1 BD 73 52 E5 48 63 33 7A 39 BF C5 25 AD 53 26 53 0D E4 81 51 D1 3E

</div>
</div>
</div>
</div>
