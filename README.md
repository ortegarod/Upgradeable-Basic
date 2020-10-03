This code is taken from Smart Contract Security course at https://academy.ivanontech.com/.

This simple proxy is for demonstration only and won't work as a proxy in a real project.

The setup allows for fixing errors in existing functions, but does not allow for adding functionality in the future. The proxy contract would not be able to call any new functions from the new functional contract. 

In addition, the storage contract could also not be updated which limits this basic structure's applicability.

See upgradeable-advanced for updated structure..