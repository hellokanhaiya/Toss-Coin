<style>
 
        .easy-banner {
            background-color: #ffedcd;
            padding: 28px 20px;
            display: flex;
            justify-content: space-around;
            align-items: center;
            flex-wrap: wrap;
            gap: 30px;
            margin-top:32px;
        }

        .easy-feature {
            display: flex;
            align-items: center;
            gap: 15px;
            flex: 1;
            min-width: 200px;
            max-width: 250px;
        }

        .icon {
            width: 50px;
            height: 50px;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-shrink: 0;
        }

        .icon img {
            width: 100%;
            height: 100%;
            object-fit: contain;
          filter: brightness(0) saturate(100%) invert(58%) sepia(76%) saturate(2738%) hue-rotate(342deg) brightness(99%) contrast(103%);
        }

        .feature-content h3 {
            font-size: 14px;
            font-weight: 700;
            color: #ff8d46;
            margin: 0px;
            letter-spacing: 0.5px;
        }

        .feature-content p {
            font-size: 12px;
            color: #ff8d46;
            line-height: 1.4;
                  margin: 0px;
        }

     @media (max-width: 768px) {
    .easy-banner {
        flex-direction: column;
        gap: 24px;
        padding: 30px 15px;
        align-items: center;
    }

    .easy-feature {
        width: 100%;
        max-width: 280px;
        justify-content: flex-start; /* icon + text left */
        margin: 0 auto;             /* block centered */
    }
}

    </style><div class="easy-banner">
        <div class="easy-feature">
            <div class="icon">
                <img src="https://img.clevup.in/shy-pub/461833/truck-svgrepo-com%201.png" alt="Free Delivery">
            </div>
            <div class="feature-content">
                <h3>FREE DELIVERY</h3>
                <p>Free shipping above 499/-</p>
            </div>
        </div>

        <div class="easy-feature">
            <div class="icon">
                <img src="https://img.clevup.in/375741/static/easy-return.png" alt="Easy Return">
            </div>
            <div class="feature-content">
                <h3>EASY RETURN</h3>
                <p>Return guarantee under 7 days</p>
            </div>
        </div>

        <div class="easy-feature">
            <div class="icon">
                <img src="https://img.clevup.in/shy-pub/461833/Vector.png" alt="Payments">
            </div>
            <div class="feature-content">
                <h3>PAYMENTS</h3>
                <p>100% payment security</p>
            </div>
        </div>

        <div class="easy-feature">
            <div class="icon">
                <img src="https://img.clevup.in/shy-pub/461833/money-earn-svgrepo-com%201.png" alt="Special Offer">
            </div>
            <div class="feature-content">
                <h3>SPECIAL OFFER</h3>
                <p>Special Discount on prepaid order</p>
            </div>
        </div>
    </div>
