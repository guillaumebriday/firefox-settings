# Firefox-settings

Firefox advanced settings for increased privacy and security

## Configure DNS over HTTPS

    network.trr.mode = 2
    network.trr.uri = https://doh.paesa.es/dns-query

## Enable Encrypted SNI

    network.security.esni.enabled = true

## Enable Delegated Credentials

    security.tls.enable_delegated_credentials = true

## Disable TLS 1.0 and TLS 1.1

    security.tls.version.min = 3

## Disable Weak TLS Ciphersuites

    security.ssl3.ecdhe_ecdsa_aes_128_sha = false
    security.ssl3.ecdhe_ecdsa_aes_256_sha = false
    security.ssl3.dhe_rsa_aes_128_sha = false
    security.ssl3.dhe_rsa_aes_256_sha = false
    security.ssl3.ecdhe_rsa_aes_128_sha = false
    security.ssl3.ecdhe_rsa_aes_256_sha = false
    security.ssl3.rsa_aes_128_gcm_sha256 = false
    security.ssl3.rsa_aes_128_sha = false
    security.ssl3.rsa_aes_256_gcm_sha384 = false
    security.ssl3.rsa_aes_256_sha = false
    security.ssl3.rsa_des_ede3_sha = false

## Resist Fingerprinting

    privacy.resistFingerprinting = true

## Enable HTTPS-Only Mode

    dom.security.https_only_mode = true
    dom.security.https_only_mode_ever_enabled = true

## Others

    network.http.sendRefererHeader = 0
    privacy.donottrackheader.enabled = true
    security.OCSP.enabled = 0