- public class MenuItem
{
    public int Id { get; set; }
    public string Name { get; set; }
    public decimal Price { get; set; }
    public int CategoryId { get; set; }
    public MenuCategory Category { get; set; }
}

public class MenuCategory
{
    public int Id { get; set; }
    public string Name { get; set; }
    public List<MenuItem> MenuItems { get; set; }
}

