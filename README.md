# as3-shared-cert-example

To tidy up the certificate and remove the newlines run this

awk 'NF {sub(/\r/, ""); printf "%s\\n",$0;}' test-shq.crt

