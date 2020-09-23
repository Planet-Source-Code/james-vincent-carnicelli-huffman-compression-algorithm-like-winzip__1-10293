<div align="center">

## Huffman Compression Algorithm \(like WinZIP\)


</div>

### Description

PKZIP, ARJ, ARC, JPEG, and a host of other programs and compressed file formats all use the Huffman coding algorithm (or similar redundancy-minimization methods) for compressing strings.

<P>With this small VB module, you can do your own compression in code -- compressing strings down to as small as 13%. Here's how easy it is:

<P STYLE="color:003399">

        Compressed = HuffmanEncode(Text1)

<BR>        Text2 = HuffmanDecode(Compressed)

</P>

<P>This simple code can be used to compress big text fields in databases, keep your data files small, or speed up transfers of data across the Internet. It can also be used as a form of encryption.

<P>The HuffmanCoding.bas module has plenty of extra information and some in-code documentation (in case you're wondering out how it works.)

<P>Please comment on this code and vote for my hard work if you like this code.

<P>

----

<BR>Updates:

<P>1 August 2000:

<LI>Rebuilt from scratch

<LI>Compression takes 28% of the time it did before

<LI>Decompression takes 19% of the time it did before

<LI>There's only one file, now (no extra class)

<LI>Much better error checking and reporting

<LI>Uses a stored checksum upon decompression to check for corruption

<LI>The code is only 455 lines, including comments!

<LI>Thanks to optimization, the code is even more convoluted :-)
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |2000-08-02 08:06:10
**By**             |[James Vincent Carnicelli](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/james-vincent-carnicelli.md)
**Level**          |Intermediate
**User Rating**    |4.8 (100 globes from 21 users)
**Compatibility**  |VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Encryption](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/encryption__1-48.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[CODE\_UPLOAD8510822000\.zip](https://github.com/Planet-Source-Code/james-vincent-carnicelli-huffman-compression-algorithm-like-winzip__1-10293/archive/master.zip)








