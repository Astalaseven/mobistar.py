# mobistar.py

Send SMSes from your Mobistar number (and factured so) from Python or Terminal

Inspired by http://business.mobistar.be/fr/professionnels/solutions-business/options-services/communiquez-avec-correspondants/pc-messenger/

## Dependencies

* Python 2
* requests (`pip install requests` or `pip install -r requirements.txt`)

## Contact support

Usage: `python2 mobistar.py Test0 "My message"`

"Test0" must be in `~/.mobistar_contacts`.

Example of `.mobistar_contacts` file:

```json
{
    "Test0": "000000000", 
    "Test1": "012345678"
}
```
