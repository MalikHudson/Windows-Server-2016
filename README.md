Windows Server Lab
==================

  

I wanted the experience of a helpdesk position to enhance my skill set. I created a virtual machine in Virtualbox, running Windows Server 2016, and began exploring.

![VirtualBox_Windows Server 2016_13_12_2022_23_27_08 (pic1).png](https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/1672533416923-5RIHTJMEV08U0J6UBIYP/VirtualBox_Windows+Server+2016_13_12_2022_23_27_08+%28pic1%29.png?format=500w)![VirtualBox_Windows Server 2016_30_12_2022_14_36_26.png](https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/1672533428174-N55VDDJV9CWABJSCAO6A/VirtualBox_Windows+Server+2016_30_12_2022_14_36_26.png?format=500w)

  

After installing the operating system, I began to add some server roles using the Server Manager. I was extremely excited. I began familiarizing myself with the various “Server Roles” such as DNS and DHCP. I have decided to dive into the “Active Directory Domain Services” (ADDS) server role. Here I can create and oversee Windows Domains. In the “Active Directory Users and Computers” console, I am creating a new Organizational Unit where my user accounts would go.  

![](https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/1fe66be8-3afa-4a13-9933-d581bbb8ec35/VirtualBox_Windows+Server+2016_31_12_2022_15_22_27.jpg?format=750w)

  

I created a user account and made myself Domain Admin. 

![VirtualBox_Windows%2BServer%2B2016_31_12_2022_15_17_10.jpg](https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/1672536863608-H2L29MMCWA2E25FN555D/VirtualBox_Windows%252BServer%252B2016_31_12_2022_15_17_10.jpg?format=500w)![VirtualBox_Windows%2BServer%2B2016_31_12_2022_15_17_33.jpg](https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/1672536853460-IIR8ABCOW84QWRW1BH2F/VirtualBox_Windows%252BServer%252B2016_31_12_2022_15_17_33.jpg?format=500w)

  

I’ve made a user account for my cat, Mickey, who isn’t allowed admin privileges, and I gave him a completely new password. Here is where I figured out the different password reset options the server provides. 

![VirtualBox_Windows+Server+2016_31_12_2022_15_14_23.jpg](https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/1672536559518-WJI145LDQK526DON4CV0/VirtualBox_Windows%2BServer%2B2016_31_12_2022_15_14_23.jpg?format=500w)![VirtualBox_Windows+Server+2016_31_12_2022_15_19_35.jpg](https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/1672536587874-OWBN14RPPOPL4NQ6QBK4/VirtualBox_Windows%2BServer%2B2016_31_12_2022_15_19_35.jpg?format=500w)

  

Lastly, I discovered where I could search for users across the domain. This search is helpful, especially in large business

environments with many users, and made finding Mickey super easy.

![](https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/cdd9a7b2-4ab2-4787-abbc-466217f3a723/VirtualBox_Windows+Server+2016_31_12_2022_16_21_09.jpg?format=750w)

Domain Search Demo: https://youtu.be/lX9K-l1FLQk

  

Below is where I created a DHCP scope, where a specified range of IP addresses are leased out to devices on the network. 
DHCP Demo: https://youtu.be/p9UPhItUQU4

![](https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/6674c849-fc25-45d4-a46f-2f8f92bda027/Screenshot+%2811%29.jpg?format=750w)

  

I installed two more virtual desktops onto my virtual machine. Here we have a Server manager (left), a helpdesk account (top-right), and an end-user account (bottom-right) to conduct the rest of this lab. This is to fully immerse me in an office environment. 

  

Where to navigate in Active Directory when end-user is locked out of account.

Unlock end-user account Demo: https://youtu.be/llE9Bb_dE8w
  

Where to navigate in Active Directory when an end-user’s account has expired

![Wind Serv (Expirered user acct).png](https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/1673312462549-P84QVJZ0VK44OHAI0I95/Wind+Serv+%28Expirered+user+acct%29.png?format=1500w)

![Wind Serv (expired acct pt 2).png](https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/1673312467160-HSPZTXOFQ0ZORDAWGC7D/Wind+Serv+%28expired+acct+pt+2%29.png?format=1500w)

  

Where to navigate in Active Directory when an end user’s account has been disabled

![Wind Serv (Account Enable).png](https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/1673313088813-63YNE58CTZPU8KB3G7WQ/Wind+Serv+%28Account+Enable%29.png?format=1500w)

![Wind Serv (Account Enable pt 2).png](https://images.squarespace-cdn.com/content/v1/6355d195a26c4b571b338345/1673313100561-CW6L90W1L75JVTNLIWCZ/Wind+Serv+%28Account+Enable+pt+2%29.png?format=1500w)

  

Creating shares and mapping drives.
