<template>
    <div class="cart">
        <Header/>
        <!-- Page info -->
        <div class="page-top-info">
            <div class="container text-left">
                <h4>Your cart</h4>
                <div class="site-pagination">
                    <a href="">Home</a> /
                    <a href="">Your cart</a>
                </div>
            </div>
        </div>
        <!-- Page info end -->

        <!-- cart section end -->
            <section class="cart-section spad">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-8">
                            <div class="cart-table text-left">
                                <h3>Your Cart</h3>
                                <div class="cart-table-warp">
                                    <table>
                                    <thead>
                                        <tr>
                                            <th class="product-th">Product</th>
                                            <th class="quy-th">Quantity</th>
                                            <th class="size-th">SizeSize</th>
                                            <th class="total-th">Price</th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                        <tr>
                                            <td class="product-col">
                                                <img src="img/cart/1.jpg" alt="">
                                                <div class="pc-title">
                                                    <h4>Animal Print Dress</h4>
                                                    <p>$45.90</p>
                                                </div>
                                            </td>
                                            <td class="quy-col">
                                                <div class="quantity">
                                                    <div class="pro-qty">
                                                        <span class="dec qtybtn">-</span>
                                                        <input type="text" value="1">
                                                        <span class="inc qtybtn">+</span>
                                                    </div>
                                                </div>
                                            </td>
                                            <td class="size-col"><h4>Size M</h4></td>
                                            <td class="total-col"><h4>$45.90</h4></td>
                                        </tr>
                                        <tr>
                                            <td class="product-col">
                                                <img src="img/cart/2.jpg" alt="">
                                                <div class="pc-title">
                                                    <h4>Ruffle Pink Top</h4>
                                                    <p>$45.90</p>
                                                </div>
                                            </td>
                                            <td class="quy-col">
                                                <div class="quantity">
                                                    <div class="pro-qty">
                                                        <span class="dec qtybtn">-</span>
                                                        <input type="text" value="1">
                                                        <span class="inc qtybtn">+</span>
                                                    </div>
                                                </div>
                                            </td>
                                            <td class="size-col"><h4>Size M</h4></td>
                                            <td class="total-col"><h4>$45.90</h4></td>
                                        </tr>
                                        <tr>
                                            <td class="product-col">
                                                <img src="img/cart/3.jpg" alt="">
                                                <div class="pc-title">
                                                    <h4>Skinny Jeans</h4>
                                                    <p>$45.90</p>
                                                </div>
                                            </td>
                                            <td class="quy-col">
                                                <div class="quantity">
                                                    <div class="pro-qty">
                                                        <span class="dec qtybtn">-</span>
                                                        <input type="text" value="1">
                                                        <span class="inc qtybtn">+</span>
                                                    </div>
                                                </div>
                                            </td>
                                            <td class="size-col"><h4>Size M</h4></td>
                                            <td class="total-col"><h4>$45.90</h4></td>
                                        </tr>
                                    </tbody>
                                </table>
                                </div>
                                <div class="total-cost">
                                    <h6>Total <span>$99.90</span></h6>
                                </div>
                            </div>
                        </div>
                        <div class="col-lg-4 card-right">
                            <form class="promo-code-form">
                                <input type="text" placeholder="Enter promo code">
                                <button>Submit</button>
                            </form>
                            <a href="" class="site-btn">Proceed to checkout</a>
                            <a href="" class="site-btn sb-dark">Continue shopping</a>
                        </div>
                    </div>
                </div>
            </section>
        <!-- cart section end -->
        <RelatedProduct/>
        <Footer/>
    </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'
import RelatedProduct from '@/components/RelatedProduct.vue'

export default {
    name:'Cart',
    components:{
        Header,
        Footer,
        RelatedProduct
    }
}
</script>