# data_scraping

used code and advice from stack overflow to create this block of code:
def extract_text(soup):
    texts = soup_obj.findAll(text=True)
    return u' '.join(t.strip() for t in texts)
scraped = extract_text(soup_obj)
print(scraped)

also derived basic structures from in-class activity practice code and zoom lectures
