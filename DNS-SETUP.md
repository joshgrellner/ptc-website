# DNS Configuration for Squarespace to GitHub Pages

## In Squarespace:

1. **Log into Squarespace**
2. Go to **Settings → Domains**
3. Click on your domain (penleytransportation.com)
4. Click **Manage Domain** → **Advanced** → **Manage DNS**

## Add These DNS Records:

### Remove/Delete existing A records first

### Add 4 new A Records:
| Type | Host | Points To |
|------|------|-----------|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |

### Add CNAME Record for www:
| Type | Host | Points To |
|------|------|-----------|
| CNAME | www | [your-github-username].github.io |

### Example:
If your GitHub username is `joshgrellner`, the CNAME would point to:
`joshgrellner.github.io`

## In GitHub (after DNS is set):

1. Create a file named `CNAME` in your repository
2. Inside, just type: `penleytransportation.com`
3. Commit the file

## DNS Propagation:

- Changes can take 24-48 hours to fully propagate
- You can check status at: https://dnschecker.org
- Enter your domain to see global DNS status

## Testing:

Once DNS propagates, test these URLs:
- http://penleytransportation.com
- http://www.penleytransportation.com
- https://penleytransportation.com
- https://www.penleytransportation.com

All should redirect to your secure GitHub Pages site!

## Troubleshooting:

If site doesn't load after 48 hours:
1. Verify all 4 A records are correct
2. Check CNAME record format
3. Ensure GitHub Pages shows "✓ Your site is published"
4. Check for typos in domain name
5. Clear browser cache

## Support:
- GitHub Pages Help: https://docs.github.com/en/pages
- Squarespace DNS: https://support.squarespace.com/hc/en-us/articles/360002101888