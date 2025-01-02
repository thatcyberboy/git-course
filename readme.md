# this is simply a read me file

go install -v github.com/PentestPad/subzy@latest

Only required flag for run subcommand(r short version) is either --target or --targets
#good thing
--target (string) - Set single or multiple (comma separated) target subdomain/s
--targets (string) - File name/path to list of subdomains
--concurrency (integer) - Number of concurrent checks (default 10)
--hide_fails (boolean) - Hide failed checks and invulnerable subdomains (default false)
--https (boolean) - Use HTTPS by default if protocol not defined on targeted subdomain (default false)
--timeout (integer) - HTTP request timeout in seconds (default 10)
--verify_ssl (boolean) - If set to true, it won't check site with invalid SSL