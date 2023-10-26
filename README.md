# FormRulesClass

This is a flutter and Dart Rules package demonstration code. The package is available at https://pub.dev/packages/rules.

This form checks for basic validation such as NotNull , email validation , PhNo validation , PinCode validation and Other validatiosn can be customized from the available Rules.

Available Rules:
String name; // mandatory

bool isRequired;

bool isEmail;

bool isUrl;

bool isPhone;

bool isIp;

bool isNumeric;

bool isNumericDecimal;

bool isAlphaSpace;

bool isAlphaNumeric;

bool isAlphaNumericSpace;

RegExp regex;

int length;

int minLength;

int maxLength;

double greaterThan;

double greaterThanEqualTo;

double lessThan;

double lessThanEqualTo;

double equalTo;

double notEqualTo;

List<double> equalToInList;

List<double> notEqualToInList;

String shouldMatch;

String shouldNotMatch;

bool shouldPass(String value);

List<String> inList;

List<String> notInList;
