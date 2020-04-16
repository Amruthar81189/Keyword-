# Keyword-
Custom Keyword 
public class fblogin {


	@Keyword
	public void loginIntoApplication(String applicationUrl,String UserName, String Password){
		WebUI.openBrowser('')

		WebUI.navigateToUrl('www.facebook.com')

		WebUI.setText(findTestObject('face book/Page_Facebook  log in or sign up/input_Password_email'), '7795464994')

		WebUI.setEncryptedText(findTestObject('face book/Page_Facebook  log in or sign up/input_Password_pass'), 'enVVIm82XVqQ/m4gTjomXw==')

		WebUI.click(findTestObject('face book/Page_Facebook  log in or sign up/label_Password_loginbutton'))
	}
}
