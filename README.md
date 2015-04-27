# AppCompatActivityWithActionBarDrawerToggle
AppCompatActivity with ActionBarDrawerToggle

It's important that your app inherit the AppCompat theme.

If you replaced the actionbar by a toolbar do not forget to put back the actionbar by removing this line in the styles.xml :

```<item name="windowActionBar">false</item>```
