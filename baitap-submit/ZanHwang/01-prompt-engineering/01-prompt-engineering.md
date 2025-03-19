- Prompt 1
You're a chemistry teacher at a secondary school. You need create a 4-answer multiple choice test to review lesson with 20 questions, of which 10 will be at the recognition level, 5 will be at the easy level, 3 will be at the medium level, and 2 will be at the difficult level. 
Lesson is "Bài 8: Acid" in "Khoa học tự nhiên 8" of "Kết nối tri thức"
chemical names need to be changed to fit the new program
Note:1. use n= V/24,79 instead of n = V/22,4
     2. chemical names need to be changed to fit the new program
        eg: old: acid
        new: acid
    
- Prompt 2
i will give you a Paragraph  in """ """ . You need help me "Analyze first, then expand on the writing . You must write clearly, in an easy-to-understand manner, and appropriately for the context and tone.
"""Băng giá hình thành từ khuya 18-3 và rạng sáng nay 19-3 ở đỉnh núi Tà Xùa khi nhiệt độ ngoài trời xuống 0 độ C. Lần gần nhất băng giá xuất hiện ở các đỉnh núi cao như Phia Oắc (Cao Bằng), Y Tý (Lào Cai), Tà Xùa (Yên Bái) là trong đợt không khí lạnh ngày 11-1-2025."""
- Prompt 3
These are the comments about the iPhone 15, i will put it in """ """: 
"""Battery life is not as impressive as expected, especially under heavy use. Dynamic Island is becoming more useful with app integrations, but still feels like a gimmick at times. The new titanium frame makes the phone feel lighter, but some people find it less premium than stainless steel. Camera zoom 5x is great, but not as powerful as Samsung’s 10x optical zoom. The overheating issue still occurs under intensive tasks like gaming and video recording. The USB-C port is a welcome change, but charging speed is still not as fast as some Android flagships. The Always-On Display is useful, but it drains battery more than expected. The action button is customizable, but some users miss the traditional mute switch. iOS is smooth, but some people feel limited by the lack of customization compared to Android. The price is too high, especially for the base storage version. Speakers are loud and clear, but bass is weaker compared to some competitors. The ProMotion 120Hz display is smooth, but most users don’t notice much difference in daily use. Face ID is super fast, but still no in-display fingerprint option for added convenience. The new color options look sleek, but some users report that the titanium frame scratches easily. Despite all the upgrades, the experience is not drastically different from the iPhone 14 Pro Max.""" 
Help me classify into good and bad comment, summarize, and count the number of comment 
Note: If the first part of the comment is positive and the second part is negative, it is a bad comment. If the first part is negative but the second part is positive, it is a good comment
- Prompt 4
@router.get("/{id}",response_model=schemas.Post)
def get_post(id: int, db: Session = Depends(get_db)):  
    post=db.query(models.Post).filter(models.Post.id == id).all() 
    if not post:
        raise HTTPException(
            status_code=status.HTTP_404_NOT_FOUND,
            detail=f"Post with id: {id} was not found"
        )
    return post

Help me find and fix bug, add comment and explain this code. Reply me in vietnamese
- Prompt 5
You're tour guide. My family and I will have a vacation at Sam Son Beach, Thanh Hoa.Help me introduce popular attractions, activities, famous dishes, and visiting times.
- Prompt 6
I will give you a PDF of a book. Help me review the knowledge from this book as if you were a teacher