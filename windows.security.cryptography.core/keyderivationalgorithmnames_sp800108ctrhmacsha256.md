---
-api-id: P:Windows.Security.Cryptography.Core.KeyDerivationAlgorithmNames.Sp800108CtrHmacSha256
-api-type: winrt property
---

<!-- Property syntax
public string Sp800108CtrHmacSha256 { get; }
-->

# Windows.Security.Cryptography.Core.KeyDerivationAlgorithmNames.Sp800108CtrHmacSha256

## -description
Retrieves a string that contains "SP800_108_CTR_HMAC_SHA256".

## -property-value
String that contains "SP800_108_CTR_HMAC_SHA256".

## -remarks
Use the string retrieved by this property to set the Key Derivation Function (KDF) name when you call the [OpenAlgorithm](keyderivationalgorithmprovider_openalgorithm.md) method on the [KeyDerivationAlgorithmProvider](keyderivationalgorithmprovider.md) class. The string represents a Sp800-108 algorithm in counter mode that uses a Hashed Message Authentication Code based on the Secure Hash Algorithm 256 message digest algorithm (HmacSha256) as the underlying pseudorandom function.

To use this KDF, you must specify the appropriate parameters by calling the [BuildForSP800108](keyderivationparameters_buildforsp800108.md) method on the [KeyDerivationParameters](keyderivationparameters.md) before calling the [CreateKey](keyderivationalgorithmprovider_createkey.md) method to derive a key.

## -examples

## -see-also
[KeyDerivationAlgorithmProvider](keyderivationalgorithmprovider.md), [KeyDerivationParameters](keyderivationparameters.md)