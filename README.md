<html>
<div align="center">
  <img src="https://github.com/schnipdip/EBE/blob/main/EBE.png" width="150" height="150" /> 
</div>

<div align="center">
<a href="https://www.buymeacoffee.com/ebeapp" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a></div>
</html>

Ebe is an Android and iOS hybrid application that saves the current location in a panoramic picture with the necessary information the share and collaborate on future projects.

## Download
### [Android]
### [iOS]

## Support
For bugs, security exploits and ideas please create a new [ISSUE]

[ISSUE]: https://github.com/schnipdip/EBE/issues
[Android]: https://play.google.com/store/apps/details?id=com.ebeapp.ebe
[iOS]: https://apps.apple.com/app/ebe/id6443468551?platform=iphone

## FAQS
Question: Why can't we upload images/videos of places we visit?

Answer: This comes down to moderation. Moderating the platform for nefarious activitiy and the legal liability is too much. At some point, there may be ability to add images for personal use that's not visible by the global community and businesses can opt in to subscription plan to host a placard with four tailored and stitched photos to market their location.

Question: Why aren't there user accounts?

Answer: As simple as it would be to create user logins, it creates an attack surface. I don't want to put my users are risk of possible data leaks. The less information about the user the better in my opinion. There are different ways to identify unique users. Currently, we use Device ID's to identify users. This enables us to present users with their own tailored experience without putting them at risk.

Question: What happens if I lose my phone?

Answer: As of now, there isn't a backup method to ensure proper ownership transfer to the new device. The current solution is to save your images again from the global directory. Any images you saved, but not deleted, will be accessible in the global directory. I have been thinking of a proper backup solution to transfer ownership. Hopefully a future update will include ownership transfer functionality. Unfortunately, it will require the user to be proactive in their backups.


Question: Why can't I add custom search labels?

Answer: To prevent label abuse (bad words, inconsistent spellings, inaccurate labels) we rely on Google Vision AI to make best effort judgements on labels. It's not a perfect practice, but it does help. A future update may allow the users to append custom search labels. Google Vision AI allows images to be searchable right out of the box without the need of user input. So if you're not a proactive user in maintaining your labels, your images will have best effort labels applied to them by Google Vision AI. This seems like a good idea, but I will have to consider the possible bad actors before implementing this feature to prevent abuse.

Question: Why do I have to subscribe to get access to auto populate Land Owner and Land Owner Contact information? 

Answer: EBE utilizes an API called Open People Search to do a reverse lookup on address locations to find the most recent owner and their contact info. Unfortunately, Open People Search is relatively expensive per search. In order to prevent financial abuse, this API feature is unlocked with the subscription to help cover costs. This feature is particularly useful for power users who use EBE professionally. Free users still have access to manually add all of that information themselves, the process just isn't automated. 

