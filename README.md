This is a full native iPhone app to create realtime, text based group or private chat with Parse and Firebase.

![Chat](http://relatedcode.com/github/chat821.png)

## FEATURES

- Live chat between multiple devices
- Group chat functionality
- Private chat functionality
- Single or Multiple recipients
- Full realtime actions - latency less than 100 ms
- No backend programming needed
- Native and easy to customize user interface
- Push Notification support
- Deep linking for Push Notification (<i>coming soon</i>)
- Login with Email
- Login with Facebook
- Login with Twitter
- Sending text messages
- Sending pictures
- Sending videos
- Sending audio messages
- Sending location
- Sending large emojis
- MD5 checksum for media messages
- Media files cached locally
- AES-256 encryption
- Address Book friend list
- Invite functionality - SMS, email
- Facebook friend list (list only registered users)
- Realtime recent view for ongoing chats
- Map view for shared locations
- Picture view for pictures
- Basic Settings view included
- Profile view for users
- Group settings view for groups
- Blocked view for blocked users
- Privacy Policy view
- Terms of Service view
- Facebook profile picture grabbed automatically
- Picture, video and audio upload progress indicator
- Video length limit possibility
- Copy and paste text messages
- Send button is enabled/disabled automatically
- Arbitrary message sizes
- Data detectors - phone numbers, links, dates
- Timestamps possibilities
- Hide keyboard with swipe down
- Smooth animations
- Send/Receive sound effects
- Deployment target: iOS 8+
- Supported devices: iPhone 4S/5/5C/5S/6/6 Plus/6S/6S Plus

###PREMIUM
- Media message reload option if download is failed - **[Premium only](http://relatedcode.com/premium)**
- Sending stickers - **[Premium only](http://relatedcode.com/premium)**
- Dynamic password generation - **[Premium only](http://relatedcode.com/premium)**
- Load earlier messages - **[Premium only](http://relatedcode.com/premium)**
- Typing indicator - **[Premium only](http://relatedcode.com/premium)**
- Message delivery receipt - **[Premium only](http://relatedcode.com/premium)**
- Message read receipt - **[Premium only](http://relatedcode.com/premium)**
- Save picture messages to device - **[Premium only](http://relatedcode.com/premium)**
- Save video messages to device - **[Premium only](http://relatedcode.com/premium)**
- Save audio messages to device - **[Premium only](http://relatedcode.com/premium)**
- Delete read and unread messages - **[Premium only](http://relatedcode.com/premium)**
- Block user functionality - **[Premium only](http://relatedcode.com/premium)**
- Report user functionality - **[Premium only](http://relatedcode.com/premium)**

---

## REQUIREMENTS

- Xcode 7+
- iOS 8+
- ARC



## INSTALLATION

###Podfile
`pod 'Parse'`  
`pod 'ParseFacebookUtilsV4'`  
`pod 'ParseTwitterUtils'`  
`pod 'FBSDKCoreKit', '~> 4.10'`  


**1.,** You need the latest **Parse SDK** (use Pods).

**2.,** You also need the latest **Firebase SDK**. (Already included, but you can download from [here](https://www.firebase.com/docs/ios/alternate-setup.html)).

**Rules**:   

	{
	    "rules": {
	        ".read": true,
	        ".write": true,
	        "Recent": {
	          ".indexOn": ["userId", "groupId"]
	        }
	    }
	}
**3.,** You also need the latest **Facebook SDK** (use Pods).

**4.,** You also need several external libraries which are included. But if you need, you can download them from here:

	https://github.com/AFNetworking/AFNetworking
	https://github.com/fernandospr/CoreLocationUtils
	https://github.com/ideaismobile/IDMPhotoBrowser
	https://github.com/hackiftekhar/IQAudioRecorderController
	https://github.com/jessesquires/JSQMessagesViewController
	https://github.com/jessesquires/JSQSystemSoundPlayer
	https://github.com/jdg/MBProgressHUD
	https://github.com/relatedcode/ProgressHUD
	https://github.com/RNCryptor/RNCryptor
	https://github.com/rnystrom/RNGridMenu
	https://github.com/rs/SDWebImage

To use these libraries, just add the downloaded directories to your project.

**5.,** You need to prepare your own [Parse server](https://github.com/ParsePlatform/parse-server).

**6.,** You need to use your own [Firebase account](https://www.firebase.com/signup).

**7.,** You need to [register](https://developers.facebook.com/apps) your app at Facebook. More info about how to [configure](https://developers.facebook.com/docs/ios/getting-started) Facebook.

**8.,** You need to [configure](https://www.parse.com/tutorials/ios-push-notifications) Push Notification.

**9.,** Please replace the existing Parse account details in *AppDelegate.m*.

**10.,** Please replace the existing Firebase account details in *AppConstant.h*.

**11.,** Please replace the existing Facebook account details in *Info.plist*.

**12.,** Please replace the existing Twitter account details in *AppDelegate.m*.


## LICENSE

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
