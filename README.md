# CF Reverse Proxy

This small proxy app helps you to make arbitrary HTTP backends/services available over CF.

## How to use

1. Clone this repo
1. Get the Url to the backend Service you want to proxy. 
(Example in the Swisscom Application Cloud - by logging into https://console.developer.swisscom.com/ and creating a Service Key for the desired/initiated Service.)
1. Change the entry `BACKEND_URL` in `manifest.yml` to the backend you want to reverse-proxy.
1. Run `cf push`
