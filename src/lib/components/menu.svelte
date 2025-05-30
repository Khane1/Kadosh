<script>
    let baked = [
        {
            color: "bg-[#D4C4C2]",
            title: "Cookies",
            textcolor: "text-[#481E21]",
            itemsCountBg: "bg-[#240406]",
            values: [
                {
                    name: "Chocolate Chip",
                    image: "https://images.unsplash.com/photo-1499636136210-6f4ee915583e",
                    price: 3500,
                },
                {
                    name: "Oatmeal Raisin",
                    image: "https://images.unsplash.com/photo-1737285898767-ebe07ed4ed12?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D",
                    price: 3500,
                },
                {
                    name: "Sugar",
                    image: "https://images.unsplash.com/photo-1558961363-fa8fdf82db35",
                    price: 3000,
                },
                {
                    name: "Peanut Butter",
                    image: "https://images.unsplash.com/photo-1548365328-8c6db3220e4c",
                    price: 4000,
                },
                {
                    name: "Double Chocolate",
                    image: "https://images.unsplash.com/photo-1618923850107-d1a234d7a73a",
                    price: 4000,
                },
            ],
        },
        {
            color: "bg-[#A8C8CC]",
            title: "Cake",
            textcolor: "text-[#135C66]",
            itemsCountBg: "bg-[#005662]",
            values: [
                {
                    name: "Chocolate",
                    image: "https://images.unsplash.com/photo-1578985545062-69928b1d9587",
                    price: 45000,
                },
                {
                    name: "Vanilla",
                    image: "https://images.unsplash.com/photo-1464349095431-e9a21285b5f3",
                    price: 40000,
                },
                {
                    name: "Red Velvet",
                    image: "https://images.unsplash.com/photo-1635117492718-695a17a5977a?q=80&w=2080&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D",
                    price: 50000,
                },
                {
                    name: "Carrot",
                    image: "https://images.unsplash.com/photo-1621303837174-89787a7d4729",
                    price: 45000,
                },
                {
                    name: "Black Forest",
                    image: "https://images.unsplash.com/photo-1571115177098-24ec42ed204d",
                    price: 55000,
                },
            ],
        },
        {
            color: "bg-[#DDC7FE]",
            title: "Bretzel",
            textcolor: "text-[#412B5A]",
            itemsCountBg: "bg-[#220E37]",
            values: [
                {
                    name: "Classic Salt",
                    image: "https://plus.unsplash.com/premium_photo-1671455916389-0964887400b9?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D",
                    price: 6000,
                },
                {
                    name: "Cheese",
                    image: "https://cloudykitchen.com/wp-content/uploads/2022/06/pretzels-with-mustard.jpg",
                    price: 7000,
                },
                {
                    name: "Garlic",
                    image: "https://images.unsplash.com/photo-1678646142939-31a5a9e91f91?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTB8fGJyZXR6ZWx8ZW58MHx8MHx8fDA%3D",
                    price: 7000,
                },
                {
                    name: "Cinnamon Sugar",
                    image: "https://images.unsplash.com/photo-1727691165307-69ac64d2ebd9?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NHx8YnJldHplbHxlbnwwfHwwfHx8MA%3D%3D",
                    price: 7000,
                },
                {
                    name: "Everything",
                    image: "https://plus.unsplash.com/premium_photo-1671455916389-0964887400b9?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NXx8YnJldHplbHxlbnwwfHwwfHx8MA%3D%3D",
                    price: 8000,
                },
            ],
        },
        {
            color: "bg-[#E8E8E8]",
            title: "Pastries",
            textcolor: "text-[#313131]",
            itemsCountBg: "bg-[#313131]",
            values: [
                {
                    name: "Croissant",
                    image: "https://images.unsplash.com/photo-1555507036-ab1f4038808a",
                    price: 8000,
                },
                {
                    name: "Danish",
                    image: "https://images.unsplash.com/photo-1509365465985-25d11c17e812",
                    price: 7000,
                },
                {
                    name: "Eclair",
                    image: "https://images.unsplash.com/photo-1582217308209-2207886c55bd?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D",
                    price: 9000,
                },
                {
                    name: "Cinnamon Roll",
                    image: "https://images.unsplash.com/photo-1645995575875-ea6511c9d127?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NHx8Q2lubmFtb24lMjBSb2xsfGVufDB8fDB8fHww",
                    price: 8000,
                },
                {
                    name: "Apple Turnover",
                    image: "https://images.unsplash.com/photo-1657313938000-23c4322dbe22?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8QXBwbGUlMjBUdXJub3ZlcnxlbnwwfHwwfHx8MA%3D%3D",
                    price: 8000,
                },
            ],
        },
        {
            color: "bg-[#F2DA26]",
            title: "Croissant",
            textcolor: "text-[#491C00]",
            itemsCountBg: "bg-[#350408]",
            values: [
                {
                    name: "Classic Butter",
                    image: "https://images.unsplash.com/photo-1555507036-ab1f4038808a",
                    price: 8000,
                },
                {
                    name: "Chocolate",
                    image: "https://images.unsplash.com/photo-1549903072-7e6e0bedb7fb",
                    price: 9000,
                },
                {
                    name: "Almond",
                    image: "https://images.unsplash.com/photo-1530610476181-d83430b64dcd",
                    price: 9000,
                },
                {
                    name: "Ham & Cheese",
                    image: "https://plus.unsplash.com/premium_photo-1692913216152-790e80ddc9e8?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NXx8Y3JvaXNzYW50JTIwSGFtJTIwJTI2JTIwQ2hlZXNlfGVufDB8fDB8fHww",
                    price: 10000,
                },
                {
                    name: "Pain au Chocolat",
                    image: "https://images.unsplash.com/photo-1608198093002-ad4e005484ec",
                    price: 9000,
                },
            ],
        },
        {
            color: "bg-[#FDCAB0]",
            title: "Bagel",
            textcolor: "text-[#771E06]",
            itemsCountBg: "bg-[#7C2804]",
            values: [
                {
                    name: "Plain",
                    image: "https://plus.unsplash.com/premium_photo-1663842114888-19434f991233?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D",
                    price: 5000,
                },
                {
                    name: "Sesame",
                    image: "https://images.unsplash.com/photo-1627308595260-6fad84c40413?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8YmFnZWx8ZW58MHx8MHx8fDA%3D",
                    price: 5500,
                },
                {
                    name: "Everything",
                    image: "https://images.unsplash.com/photo-1586444248902-2f64eddc13df",
                    price: 6000,
                },
                {
                    name: "Onion",
                    image: "https://images.unsplash.com/photo-1590368746679-a403ad57e684",
                    price: 5500,
                },
                {
                    name: "Blueberry",
                    image: "https://www.theconsciousplantkitchen.com/wp-content/uploads/2025/02/Blueberry-Bagels.jpg",
                    price: 6000,
                },
            ],
        },
    ];
    let selectedCategory = baked[0].title;

</script>

<div
    class="flex items-start flex-col md:flex-row justify-center rounded-3xl md:rounded-[4em] p-4 pt-12 sm:p-8 md:p-12 lg:p-20 m-4 sm:m-6 md:m-8 lg:m-10"
>
    <div class="w-full md:w-1/3">
        <img
            class="object-cover w-full h-[200px] sm:h-[300px] md:h-[350px] lg:h-[380px] rounded-4xl shadow-xl"
            src="https://images.unsplash.com/photo-1632552544552-3ca612a328ac?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
            alt=""
        />
    </div>
    <div class="space-y-5 w-full md:w-1/3 text-start mt-6 md:mt-0 md:ml-10">
        <div
            class=" specialFont text-3xl sm:text-4xl md:text-3xl lg:text-5xl text-center md:text-left"
        >
            YOUR ONLY DOSE OF DELIGHT
        </div>
        <div class="specialFont">Featured Item</div>
        <div>
            <div
                class="flex flex-col sm:flex-row justify-between items-center gap-4 sm:gap-6"
            >
                <img
                    class="object-cover w-full sm:w-1/3 h-[150px] sm:h-[105px] rounded-xl"
                    src="https://plus.unsplash.com/premium_photo-1677596908545-28f516310543?q=80&w=1976&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                    alt=""
                />
                <div class="text-center sm:text-left">
                    <div class="specialFont text-xl sm:text-2xl">
                        Bread Buns
                    </div>
                    <div class="text-sm sm:text-base">Butter Flavor</div>
                </div>
                <div class="hidden sm:block">|</div>
                <div class="specialFont text-lg sm:text-xl text-[#541214]">
                    ugx. 5,000
                </div>
            </div>
            <div class="pt-5">
                Indulge in our freshly baked bread buns, made with premium
                ingredients and baked to perfection. Each bite delivers a rich,
                buttery flavor that melts in your mouth, making it the perfect
                treat for any time of day.
            </div>
        </div>
    </div>
</div>
<div class=" pt-12 p-10 md:py-12 lg:py-20 md:flex w-full justify-between">
    <div class="specialFont md:text-6xl text-3xl md:mb-0 mb-5 capitalize">
        Product we bake<br /> Here Daily
    </div>
    <div
        class="grid grid-cols-2 md:grid-cols-3 gap-5 md:w-1/2 specialFont text-center"
    >
        {#each baked as item}
            <button
                type="button"
                class="{item.color} {item.itemsCountBg} md:px-4 md:py-5 rounded-full cursor-pointer"
                on:click={() =>
                    (selectedCategory =
                        item.title === selectedCategory ? "" : item.title)}
                on:keydown={(e) => {
                    if (e.key === "Enter" || e.key === " ") {
                        selectedCategory =
                            item.title === selectedCategory ? "" : item.title;
                    }
                }}
            >
                {item.title}
                <span
                    class="rounded-full md:px-6 px-3 py-2 {item.itemsCountBg}   font-semibold"
                >
                    <span class="text-white opacity-90">
                        {item.values.length}</span
                    >
                </span>
            </button>
        {/each}
    </div>
</div>
<div
    class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6 w-full pt-12 p-10 md:py-12 lg:py-20"
>
    {#each baked as category}
        {#if selectedCategory === category.title}
            {#each category.values as item}
                <div class="">
                    <div
                        class="{category.color} rounded-4xl shadow-md overflow-hidden"
                    >
                    <div class="flex items-center justify-between">
                        <div class="relative w-full">
                            <span
                                class={`${category.color} px-3 py-1 rounded-full text-sm absolute top-4 right-4 z-10`}
                            >
                                {category.title}
                            </span>
                            <img
                                src={item.image ||
                                    "https://via.placeholder.com/300x200"}
                                alt={item.name}
                                class="w-full h-72 object-cover"
                            />
                        </div>                        </div>
                    </div>                    <div class="p-4">
                        <div class="flex justify-between">
                            <h3 class="specialFont text-xl mb-2">
                                {item.name}
                            </h3>
                            <span class="font-semibold specialFont"
                                >ugx. {item.price}</span
                            >
                        </div>
                    </div>
                </div>
            {/each}
        {/if}
    {/each}
</div>
