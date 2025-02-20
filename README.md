# **<p align="center">Skip TPM Check on Dynamic Update**
**<p align="center">How to Bypass Windows 11's TPM, CPU and RAM Requirements**
  
Microsoft has some strict hardware requirements that your PC must meet to install Windows 11, including TPM 2.0 support. This means that not only older computers, but virtual machines will refuse to upgrade from Windows 10, giving you a message that "this PC doesn't currently meet Windows 11 system requirements." 

Fortunately, there are several simple ways you can get bypass Windows 11's TPM, RAM and other requirements. If you're doing a clean install with a Windows 11 ISO, you can edit the registry in the middle of the setup process and tell it to skip requirement checks. We'll show you how to modify the registry in the first section below.

If you have Windows 10 or an earlier build of Windows 11 installed on a PC that didn't meet the requirements (perhaps a VM), you try to update to a new build with Windows Update and you get the "doesn't meet requirements" error message, there's a workaround for that. As we'll detail in the third section below, a script from AveYo's Media Creation tool [Github Page](https://github.com/Padaki89/Skip-TPM-Check-on-Dynamic-Update/tree/main) will allow you to bypass Windows 11's TPM requirement even with Windows Update. 

> [!NOTE]
> _That Microsoft also has also created an official registry hack to bypass TPM 2.0 and CPU requirements for an in-place upgrade. However, this method still requires at least TPM 1.2 so, if you have no TPM at all, it's worthless._

### <p align="center">Support Made with Trust ❤️</p>
