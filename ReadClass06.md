Jose Cardozo
01/23/2023

https://www.jscape.com/blog/implementing-the-cia-triad-when-transferring-files-through-the-internet



Applying The CIA Triad To Your Enterprise File Transfer

As one of the basic building blocks of information security, the CIA Triad is likewise a vital piece in establishing secure enterprise file transfers. In this post, we explain what the CIA Triad is and how you can apply it to your B2B data transfers.
The CIA Triad refers to three basic principles/objectives in information security, namely: confidentiality, integrity, and availability. It's been proven that, in order to establish a secure system, you need to achieve these three objectives. Let me explain each one first and why they are crucial to business file transfers.
Confidentiality
In the context of information security, confidentiality refers to the principle of restricting access to or knowledge of certain pieces of information to certain individuals. There are several reasons for doing so. For example:
  A company might not want competitors to know its trade secrets, key personnel salaries, list of customers, products in development, or sales and marketing plans
  A law firm might want to preserve attorney-client privilege
  A healthcare organization may want to secure ePHI and comply with HIPAA / HITECH requirements
  Trading partners might want to keep transaction details between themselves and so on.
Integrity
The second member of the CIA triad, integrity (which means data integrity) pertains to the principle of preventing data from being tampered. Data integrity is particularly crucial in business transactions where unauthorized alterations to data (whether intentional or accidental) can lead to disputes, report misstatements, and (in the case of fraudulent alterations) financial losses.
Availability
Ok. Let's say you're able to preserve the confidentiality and integrity of your data at all times. But what if there are times when you need it and the data becomes inaccessible? That can be a problem, right? In the case of file transfers, data access problems can be due to a variety of reasons. Power interruptions, network disruptions, server failures, missing files, DDoS attacks, and natural disasters are just some of the many unfortunate events that can render data inaccessible.
CIA-Triad-in-One
Normally, in order to apply all three elements of the CIA Triad, you would need to employ disparate solutions and integrate them. The problem with this approach is that it can be quite complex and would therefore require considerable time and expertise before you can come up with a complete solution.



What Are MD5, SHA-1, and SHA-256 Hashes, and How Do I Check Them?

You’ll sometimes see MD5, SHA-1, or SHA-256 hashes displayed alongside downloads during your internet travels, but not really known what they are. These seemingly random strings of text allow you to verify files you download aren’t corrupted or tampered with. You can do this with the commands built into Windows, macOS, and Linux.
How Hashes Work, and How They’re Used for Data Verification
Hashes are the products of cryptographic algorithms designed to produce a string of characters. Often these strings have a fixed length, regardless of the size of the input data. Take a look at the above chart and you’ll see that both “Fox” and “The red fox jumps over the blue dog” yield the same length output.

Now compare the second example in the chart to the third, fourth, and fifth. You’ll see that, despite a very minor change in the input data, the resulting hashes are all very different from one another. Even if someone modifies a very small piece of the input data, the hash will change dramatically.

How to Compare Hash Functions on Any Operating System
With that in mind, let’s look at how to check the hash of a file you downloaded, and compare it against the one you’re given. Here are methods for Windows, macOS, and Linux. The hashes will always be identical if you’re using the same hashing function on the same file. It doesn’t matter which operating system you use.
