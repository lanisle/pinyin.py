pinyin.py
=========

汉字转拼音,With Python


Example:

    from pinyin import PinYin
    
    test = PinYin()
    test.load_word()
    test.hanzi2pinyin(string='钓鱼岛是中国的')


Out:

    diao-yu-dao-shi-zhong-guo-de
