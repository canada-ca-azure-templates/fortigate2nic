Manual execution of validation does like this:

..\..\..\Core\deployments\scripts\manual-copy.ps1 -templateLibrarySrc ..\template\ -templateLibraryDst fortigate4NIC/bernard-dev -storageRG PwS2-Infra-Storage-RG -storageAccountName azpwsdeploytpnjitlh3orvq -containerName library-dev

then

.\validate-manual.ps1 -templateLibraryName fortigate4NIC -templateLibraryVersion bernard-dev