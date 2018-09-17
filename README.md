RSItemFinder
============

Adds methods for finding RS items.
```pascal
function TRSInventory.FindAll(Identifers: TStringArray): TIntegerArray; overload;
function TRSInventory.FindAll(Identifer: String): TIntegerArray; overload; 
function TRSInventory.Find(Identifers: TStringArray): Int32; overload;
function TRSInventory.Find(Identifer: String): Int32; overload;
function TRSInventory.Count(Identifers: TStringArray): Int32; overload;
function TRSInventory.Count(Identifer: String): Int32; overload;
function TRSInventory.CountStack(Identifer: String): Int32;
function TRSInventory.Click(Identifers: TStringArray; Option: String = ''): Boolean; overload;
function TRSInventory.Click(Identifer: String; Option: String = ''): Boolean; overload;
function TRSBankScreen.Find(Identifers: TStringArray): Int32; overload;
function TRSBankScreen.Find(Identifer: String): Int32; overload;
function TRSBankScreen.Withdraw(Identifier: String; Amount: Int32; UpText:TStringArray=[]; Mode: EBankButton = bbItem): Boolean; overload;
function TRSBankScreen.Count(Identifer: String): Int32;
function TRSBankScreen.CountStack(Identifer: String): Int32;
```

- `Identifer` can be either the item ID or name. 
- Item images can be found in `item-images/`
- Item names can be found in `item-images/items.txt`
